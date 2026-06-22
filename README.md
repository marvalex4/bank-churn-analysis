# Bank Customer Churn Analysis & Prediction

## Overview
A complete end to end data analysis project combining Python EDA, 
machine learning and Power BI dashboards to analyze and predict 
bank customer churn across 10,000 customers in France, Germany 
and Spain.

## Project Structure
This project is divided into three parts:

### Part 1 : Exploratory Data Analysis (Python)
- Overall churn rate analysis
- Age distribution of churned vs retained customers
- Account balance comparison
- Churn rate by country
- Churn rate by number of products
- Churn rate by active membership status

### Part 2 : Machine Learning Model (Python)
- Logistic Regression model
- Random Forest model
- Model comparison using ROC AUC scores
- Feature importance analysis

### Part 3 : Power BI Dashboard
- Page 1: Churn Overview
- Page 2: Customer Demographics
- Page 3: Financial Analysis
- Page 4: Model Insights

## Model Performance
- **Best Model:** Random Forest
- **Accuracy:** 86.60%
- **ROC AUC Score:** 0.8576
- **Most Important Churn Factor:** Age

## Key Insights
- Overall churn rate is 20.4%
- Germany has the highest churn rate at ~32%
- Customers aged 46-55 are most likely to churn
- Inactive members churn at double the rate of active members
- Customers with 3 or 4 products have very high churn rates
- Churned customers have higher average balances
- Age is the strongest predictor of churn

## Recommendations
- Target inactive members with re-engagement campaigns
- Offer product bundles to single product customers
- Develop Germany specific retention strategies
- Create special programs for middle aged customers
- Flag high balance customers showing inactivity signs

## Tools Used
- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Power BI Desktop
- DAX (Data Analysis Expressions)

## Dataset
- Churn_Modelling.csv (sourced from Kaggle)
- 10,000 bank customer records

## Files
- bank_churn_analysis.ipynb - Python EDA and ML notebook
- Bank_Churn_Dashboard.pbix - Power BI dashboard
- Bank_Churn_Dashboard.pdf - Exported dashboard
- Churn_Modelling.csv - Dataset

## Author
Marvis Obanor
