# Data Center Water Stress Classification

## Overview

This project develops a machine learning classification model to predict the **Surrounding Water Stress Tier** of data centers based on their operational, infrastructure, and geographical characteristics. The objective is to analyze how factors such as power usage, cooling systems, water usage, and facility location relate to the surrounding water stress level.

---

## Problem Statement

Efficient water resource management is becoming increasingly important for modern data centers. This project aims to classify the surrounding water stress tier using machine learning techniques, helping understand the relationship between data center operations and environmental conditions.

---

## Dataset Features

### Input Features (X)

- Owner_Company
- City
- Country
- Facility_Type
- Estimated_Capacity_MW
- PUE
- Cooling_System_Type
- WUE_L_per_kWh
- Daily_Electricity_Usage_MWh
- Daily_Water_Usage_Gallons

### Target Variable (Y)

- Surrounding_Water_Stress_Tier

---

## Project Workflow

- Import Required Libraries
- Load the Dataset
- Exploratory Data Analysis (EDA)
- Data Cleaning
- Handle Missing Values
- Encode Categorical Features
- Remove Outliers using the IQR Method
- Train-Test Split
- Build a Machine Learning Pipeline
- Train the Classification Model
- Evaluate Model Performance
- Perform 5-Fold Cross Validation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Model Evaluation

The model was evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score
- 5-Fold Cross Validation

### Final Performance

- **Accuracy:** ~95%
- **Precision:** ~95%
- **Recall:** ~94–95%
- **F1-Score:** ~95%

The model demonstrates excellent classification performance with balanced metrics across all water stress categories.

---

## Project Structure

```
Data-Center-Water-Stress-Classification/
│
├── Data_center_water_stress.ipynb
├── data_center_hybrid.csv
└── README.md
```

---


## Future Improvements

- Compare multiple classification algorithms
- Perform hyperparameter tuning
- Feature importance analysis
- Model deployment using Flask or Streamlit
- Interactive dashboard for predictions

---

## Author

**Balaji**

Machine Learning Engineer | Data Science | Python Developer

---

## License

This project is intended for educational and portfolio purposes.
