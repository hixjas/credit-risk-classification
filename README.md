# credit-risk-classification
# Module 12 Report Template

## Overview of the Analysis

- The purpose of this analysis is to identify the creditworthiness of borrowers by training and evaluating a model based on loan risk, using a dataset of historical lending activity from a peer-to-peer lending services company.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
- The variable we are trying to predict is the `loan_status` variable.

* Describe the stages of the machine learning process you went through as part of this analysis.
 1. Read in data
 2. Created the y label and X features
 3. Split the data into training and testing sets
 4. Created a logistic regression model


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

## Classification Report Summary

| Label | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| **0 (Healthy Loan)** | 1.00      | 0.99   | 1.00     | 18,765  |
| **1 (High-Risk Loan)** | 0.85      | 0.91   | 0.88     | 619     |
| **Accuracy** | -         | -      | 0.99     | 19,384  |
| **Macro Avg** | 0.92      | 0.95   | 0.94     | 19,384  |
| **Weighted Avg** | 0.99      | 0.99   | 0.99     | 19,384  |

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.

## Summary

Based on the classification report, the logistic regression model performs well in predicting healthy loans (100%) and reasonably well for high-risk loans (85%),
