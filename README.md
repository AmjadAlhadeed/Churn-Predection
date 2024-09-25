# Customer Churn Prediction

## Project Overview

This project focuses on predicting customer churn, which is when a customer stops using a company's service. Using a dataset with various customer features, we build a machine learning model to predict whether a customer is likely to churn.

## Dataset Information

The dataset contains the following key features:

- **CustomerID**: Unique ID for each customer.
- **Gender**: The gender of the customer (Male/Female).
- **SeniorCitizen**: Whether the customer is a senior citizen (1 for Yes, 0 for No).
- **Tenure**: Number of months the customer has been with the company.
- **PhoneService**: Whether the customer has a phone service (Yes/No).
- **MonthlyCharges**: The monthly charges for the customer.
- **TotalCharges**: Total charges over the entire tenure.
- **Churn**: Whether the customer has churned (Yes/No).

## Key Features of the Project

- **Data Cleaning & Preprocessing**:
  - Handle missing values and convert categorical variables into numeric format (e.g., One-Hot Encoding).
  
- **Exploratory Data Analysis (EDA)**:
  - Analyze the distribution of churn by customer features such as tenure, monthly charges, and senior citizen status.
  - Identify the correlation between customer features and churn.

- **Model Building**:
  - Train a classification model (e.g., Logistic Regression, Random Forest, etc.) to predict customer churn.
  
- **Model Evaluation**:
  - Use metrics such as accuracy, precision, recall, and F1-score to evaluate model performance.

## Installation & Requirements

To run this project, you will need Python and the following libraries:

- **Pandas**: For data manipulation.
- **Matplotlib** and **Seaborn**: For data visualization.
- **Scikit-learn**: For model building and evaluation.
