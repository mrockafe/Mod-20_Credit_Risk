# Module 12 Report Template

## Overview of the Analysis

The analysis aimed to leverage machine learning models to assess the creditworthiness of borrowers based on historical lending data from a peer-to-peer lending platform. The objective was to predict the loan status, distinguishing between healthy (low-risk) and non-healthy (high-risk) loans. The dataset featured a significant class imbalance, with a majority of entries categorized as healthy loans.

The machine learning process involved stages such as data preprocessing, model training (including Logistic Regression), and addressing the imbalance using RandomOverSampler from the imbalanced-learn library.

## Results

* Machine Learning Model 1:

Achieved an accuracy score of 99%, with precision scores of 100% for healthy loans and 85% for non-healthy loans. It exhibited a recall of 99% for healthy loans and 91% for non-healthy loans.

* Machine Learning Model 2:

Attained a 99% accuracy score. Notably, the oversampled data model significantly reduced false negatives, improving the prediction of non-healthy loans. Precision scores remained similar to Model 1, with a recall improvement for non-healthy loans.

## Summary

The model trained with balanced data (Model 2) outperformed the one trained with imbalanced data (Model 1). Model 2 showcased fewer false positives and enhanced accuracy in categorizing healthy and non-healthy loans.

Considering the lending company's preferences, minimizing false positives (misclassifying non-healthy loans as healthy) is crucial. Model 2's reduction in false positives and improvements in accuracy for both loan types make it a recommended choice for minimizing potential financial losses and misclassifications in loan assessments. The selection of the model might depend on the significance of correctly predicting healthy and non-healthy loans, and Model 2's ability to reduce false positives might be more beneficial in this context.
