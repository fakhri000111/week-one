# Customer Churn Prediction - Week 1

## Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) on the Telco Customer Churn dataset. The goal is to understand customer behaviour, identify churn patterns, and prepare insights for building machine learning models in the upcoming phases.
##  Dataset Information
- **Dataset Name:** Telco Customer Churn
- **Total Records:** 7,043 customers
- **Total Features:** 21 columns
- **Target Variable:** Churn (Yes / No)
## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Analysis Performed

### 1. Data Exploration
- Checked dataset structure and data types
- Identified missing values
- Converted TotalCharges to numeric format

### 2. Numerical Features Analysis
- Tenure distribution
- Monthly charges distribution
- Total charges vs tenure relationship

### 3. Categorical Features Analysis
- Contract type vs churn
- Internet service vs churn
- Payment method vs churn

### 4. Correlation Analysis
- Feature correlation with churn
- Heatmap visualization

## Key Findings

- Customers with **short tenure** are more likely to churn
- **Month-to-month contracts** have the highest churn rate
- Higher **monthly charges** increase churn probability
- **Fiber optic users** churn more than DSL users
- Customers using **electronic check payments** show higher churn

## Future Work
- Build machine learning models (Week 2)
- Perform feature engineering
- Handle class imbalance
- Deploy prediction system

