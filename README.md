# Linear Regression - House Prices Prediction

This project provides a complete implementation of a linear regression model to predict house prices using the [Housing Price Dataset](https://www.kaggle.com/datasets/sukhmandeepsinghbrar/housing-price-dataset) from Kaggle.

## Objective

The main goal of this project is to improve my machine learning skills by applying the complete machine learning pipeline, from data collection to prediction.

This project includes:

- Data analysis: mean calculation, outlier detection, data range inspection, feature relationships, missing value handling, and correction of data types  
- Data preprocessing: fixing incorrect column types, handling missing values, treating outliers, and normalizing selected columns  
- Feature selection  
- Model training and hyperparameter tuning  
- Model evaluation  
- Prediction

# Project Structure
```bash
House_Prices_Prediction/
│
├── data/
│ └── Housing price data.csv
│
├── Regression_Model_Code.ipynb # Full code including EDA, preprocessing, training, and evaluation
│
├── House_prediction_regression_model.pkl # Trained and saved regression model
│
├── README.md'
```

## Dataset Overview

The Housing Price Dataset contains detailed information about various real estate properties. Each record includes attributes such as:

- Number of bedrooms and bathrooms  
- Living area size  
- Lot size  
- Location details  

This dataset is useful for multiple machine learning and data analysis tasks, including:

- Predicting property prices based on relevant features  
- Identifying patterns and trends in the real estate market  
- Supporting data-driven decisions for investors, agents, and policymakers  
- Building recommendation systems for potential homebuyers  

## Tools and Technologies

- **Programming Language**: Python  
- **Libraries Used**:
  - pandas for data handling  
  - matplotlib and seaborn for visualization  
  - scikit-learn for machine learning and modeling  
  - RFECV for feature selection using recursive elimination with cross-validation  
  - MLflow for experiment tracking  
- **Model Used**: Linear Regression


