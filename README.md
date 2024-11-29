# Fraud-Detection-in-Financial-Transactions

##Overview
This project focuses on detecting fraudulent transactions in financial datasets by utilizing the XGBoost machine learning algorithm. The dataset, sourced from Kaggle's Credit Card Fraud Detection, contains over 284,807 transactions, with fraudulent cases comprising only 0.172%. This presents a significant challenge due to the class imbalance.

##Features
Data Processing and Quality Control:
Managed a highly imbalanced dataset by performing data cleaning, standardization.
Applied SMOTE (Synthetic Minority Over-sampling Technique) to handle class imbalance, ensuring better detection of minority (fraudulent) transactions.
Machine Learning Model Development:
Implemented the XGBoost model for fraud detection.
Evaluated model performance using metrics such as Recall and F1 Score.
Achieved Recall: 1.0 and F1 Score: 0.9997273742623715, indicating effective detection of fraudulent transactions.


##Methodology
Data Preprocessing:

Cleaned missing values and standardized features.
Handled class imbalance using SMOTE to ensure the model effectively learned to detect fraudulent transactions.
Model Training:

Built and trained the XGBoost model to detect fraudulent activities.
Used metrics like Recall and F1 Score to evaluate model effectiveness.


##Results
Optimized XGBoost Model Performance:
Recall: 1.0
F1 Score: 0.9997273742623715
These metrics indicate that the model achieved high recall and balanced precision-recall trade-offs, making it effective in identifying fraudulent transactions.
