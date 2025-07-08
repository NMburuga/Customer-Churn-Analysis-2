# Customer Churn Analysis - EDA and Modeling

## Overview

This project focuses on Exploratory Data Analysis (EDA) and modeling to uncover insights from the data and build predictive models to understand Customer Churn.

Customer churn, also known as customer attrition, refers to the phenomenon where customers stop doing business with a company or service. It is a critical metric for businesses as it directly impacts revenue and profitability. 
High churn rates can indicate dissatisfaction with the product or service, poor customer experience.

## Dataset

The dataset used in this project is [Data Source](https://www.kaggle.com/datasets/rjmanoj/credit-card-customer-churn-prediction/data).

Run it with Python.

It contains the following features: 

 1. RowNumber
 2. CustomerId
 3. Surname
 4. CreditScore
 5. Geography
 6. Gender
 7. Age
 8. Tenure
 9. Balance
 10. NumOfProducts
 11. HasCrCard
 12. IsActiveMember
 13. EstimatedSalary
 14. Exited

The main variables of interest is **Exited**.

## Requirements

The following libraries are required to run the notebook:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Key Features

1. Handling Imbalanced Data: The project implements techniques to help handle imbalanced data such as SMOTE, ensuring accurate predictions even when the dependent variable is underrepresented.
2. Exploratory Data Analysis (EDA): The project features a stage of Exploratory Data Analysis (EDA), where we examine the data closely to identify trends and understand the reasons behind customer churn.
3. Classification: The project employs a variety of models, including Logistic Regression, Random Forest, K-Nearest Neighbors, Support Vector Machine, XGBoost, and Gradient Boosting, to predict customer churn, with techniques such as class weighting and SMOTE used to handle class imbalance.



#### Overall:

Gradient Boosting appears to be the best model for this churn prediction task, followed closely by XGBoost. These models are able to better handle the class imbalance and provide a good balance between precision and recall. 



