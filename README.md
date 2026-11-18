# Customer Churn Analysis and Prediction

## Project Overview

This project analyzes telecom customer data to identify the key factors associated with customer churn and prepares the data for machine learning prediction.

The dataset contains **7,043 customer records** with information about customer demographics, services, contract details, payment methods, tenure, and charges.

## What I Did

- Cleaned and prepared customer data using Pandas
- Handled missing values and data types
- Performed Exploratory Data Analysis (EDA)
- Analyzed churn patterns across different customer segments
- Studied the relationship between churn and:
  - Contract type
  - Payment method
  - Tenure
  - Monthly charges
  - Total charges
  - Paperless billing
- Performed statistical analysis to identify significant relationships
- Prepared the dataset for machine learning prediction

## Key Findings

- Customers with shorter tenure showed higher churn rates.
- Contract type was strongly associated with customer churn.
- Payment method showed differences in churn behavior.
- Higher monthly charges were associated with increased churn.
- Paperless billing customers showed a higher churn rate than customers without paperless billing.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
customer-churn-prediction/
│
├── 01_customer_churn_analysis.ipynb
├── customer_churn.csv
└── README.md
```

## Dataset

The dataset contains **7,043 telecom customer records** and **21 columns** covering customer demographics, services, contracts, billing information, and churn status.

## Purpose

The main objective of this project is to understand customer churn patterns through data analysis and prepare the dataset for building a machine learning model that can predict customers who are likely to churn.

## Future Improvements

- Build and compare multiple machine learning models
- Evaluate model performance using appropriate classification metrics
- Perform feature engineering
- Tune the best-performing model
- Deploy the final churn prediction model

## Author

**Rajesh M**
