# heart_disease_prediction
# Heart Disease Prediction

This project focuses on leveraging machine learning to predict heart disease risks based on health data, enabling targeted prevention and improved healthcare strategies.

## Project Overview

Heart disease is a leading cause of mortality worldwide, making accurate prediction and prevention critical. This project uses data from the CDC’s Behavioral Risk Factor Surveillance System to analyze health factors and build predictive models for identifying individuals at risk of heart disease.

## Dataset

The dataset includes over **240,000 records** from the CDC’s Behavioral Risk Factor Surveillance System, covering variables like:
- Age
- Smoking habits
- BMI
- Physical activity
- Medical history

## Methodology

1. **Data Preprocessing**:
   - Handled missing values and balanced the dataset to address class imbalance.
   - Feature selection was performed to identify the most significant predictors.

2. **Machine Learning Models**:
   - Logistic Regression, Random Forest, and XGBoost models were trained and evaluated.
   - Hyperparameter tuning was used to improve model performance.

3. **Evaluation**:
   - Models were evaluated using metrics like accuracy, precision, recall, and F1-score.
   - XGBoost achieved the highest accuracy of **96%**.

## Key Findings

- **BMI**, **smoking**, and **age** were identified as the most influential predictors of heart disease.
- A significant correlation was found between physical inactivity and heart disease risk.
- The XGBoost model outperformed other models, providing robust predictions.



