# Mod-20_Credit_Risk
Training and testing a machine learning model on credit risk

## Overview
This project aims to assess the creditworthiness of borrowers using machine learning techniques on historical lending data from a peer-to-peer lending services company. The goal is to build a model capable of identifying the risk associated with loans, distinguishing between healthy (0) and high-risk (1) loans.

## Folder Structure
* credit_risk_classification.ipynb: Jupyter Notebook containing code for data analysis, model training, and evaluation.
* lending_data.csv: Dataset used for analysis.
  
## Analysis Summary
Data Splitting:
The lending_data.csv dataset was loaded into a Pandas DataFrame.
Features (X) were created from columns excluding the 'loan_status', and labels (y) were extracted from the 'loan_status' column.

## Logistic Regression Model with Original Data
A Logistic Regression model was trained using the original data.
Performance evaluation included:
Fitting the model with training data.
Prediction on test data.
Generating a confusion matrix and classification report.

## Key Metrics:
Accuracy: Describes overall correctness of predictions.
Precision: Measures the accuracy of positive predictions.
Recall: Indicates the ratio of correctly predicted instances among actual positives.

## Conclusion
The logistic regression models were evaluated based on their accuracy, precision, and recall. Model 2, trained with balanced data, demonstrated improved performance, especially in reducing false positives, which is crucial for minimizing risks associated with misclassifying non-healthy loans as healthy.

## Recommendation: Considering the company's objective to minimize false positives and accurately identify non-healthy loans, Model 2 trained with balanced data is recommended for deployment due to its superior performance in addressing this critical concern.
