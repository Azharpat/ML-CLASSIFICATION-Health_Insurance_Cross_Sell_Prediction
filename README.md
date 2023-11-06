# ML-CLASSIFICATION-Health_Insurance_Cross_Sell_Prediction


Certainly, here's a README template for your "Health Insurance Cross-Sell Prediction" project:

# Health Insurance Cross-Sell Prediction

## Introduction

This project focuses on predicting whether customers who have purchased health insurance from an insurance company in the past would also be interested in purchasing vehicle insurance provided by the same company. The client, an insurance company, aims to build a predictive model to optimize their communication strategy and enhance their business model and revenue.

## Problem Statement

The problem revolves around building a model that predicts the likelihood of customers showing interest in purchasing vehicle insurance. By identifying these potential customers, the insurance company can tailor its communication and marketing efforts, leading to more efficient revenue generation.

## Business Goal

The business goal of this project is to develop a predictive model that can:

- Identify customers likely to be interested in vehicle insurance.
- Plan targeted communication and marketing strategies to reach out to potential customers.
- Optimize the company's business model and increase revenue.

## Data Description

The data for this project is sourced from Kaggle and includes the following columns:

- `id`: Unique customer ID.
- `Gender`: Gender of the customer.
- `Age`: Age of the customer.
- `Driving_License`: Indicates if the customer has a driving license (0 for no, 1 for yes).
- `Region_Code`: A unique code for the customer's region.
- `Previously_Insured`: Indicates if the customer already has vehicle insurance (1 for yes, 0 for no).
- `Vehicle_Age`: Age of the customer's vehicle.
- `Vehicle_Damage`: Indicates if the customer's vehicle was damaged in the past (1 for yes, 0 for no).
- `Annual_Premium`: The annual premium amount the customer needs to pay.
- `PolicySalesChannel`: Anonymized code for the channel of outreach to the customer (e.g., different agents, over mail, over phone, in person, etc.).
- `Vintage`: The number of days the customer has been associated with the company.
- `Response`: The target variable (1 for customer interested in vehicle insurance, 0 for not interested).

## Conclusion

In conclusion, this project employs machine learning to predict customer interest in vehicle insurance. The analysis involves the use of machine learning models, including Random Forest and XGBoost, which outperformed the Logistic Regression model.

By successfully identifying potential customers interested in vehicle insurance, the insurance company can optimize its outreach efforts, improve its business model, and ultimately enhance its revenue generation.

---
