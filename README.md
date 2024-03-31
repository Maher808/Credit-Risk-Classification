# Credit-Risk-Classification Report
## Overview of the Analysis

1) Purpose of the Analysis
The purpose of this analysis was to build machine learning models to predict credit risk based on financial information provided in the dataset. The goal was to develop models that could accurately classify loans as either healthy (low risk) or high-risk based on various financial features.

) Financial Information and Prediction
The dataset contained financial information such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. The target variable we needed to predict was the loan_status, which categorized loans as either 0 (healthy) or 1 (high-risk).

3) Basic Information about Variables
Here's some basic information about the loan_status variable:
Class 0 (healthy loans): 45009 instances
Class 1 (high-risk loans): 1513 instances

4) Stages of the Machine Learning Process
Data Preparation: We loaded the dataset and split it into features (X) and target variable (y).
Model Training: We trained logistic regression models using the training data (X_train, y_train).
Model Evaluation: We evaluated the trained models using accuracy, precision, and recall scores on the testing data (X_test, y_test).

5) Methods Used
We used logistic regression as the primary algorithm for this analysis due to its suitability for binary classification problems like credit risk prediction.

6) Results
Machine Learning Model 1:
Logistic Regression:
Accuracy: 99%
Precision (class 0): 100%
Recall (class 0): 99%
Precision (class 1): 86%
Recall (class 1): 91%


## Summary

Summary
Based on the results:

Best Performing Model: The logistic regression model performed exceptionally well, achieving high accuracy, precision, and recall scores for both healthy and high-risk loans.

Performance Considerations: While the model accurately predicts both healthy and high-risk loans, it's slightly less precise in identifying high-risk loans. However, considering the importance of correctly identifying high-risk loans to reduce potential financial losses, it's crucial to prioritize recall for class 1 (high-risk loans).

Recommendation: Given its overall strong performance, we recommend using the logistic regression model for credit risk prediction tasks. However, it's essential to continuously monitor and improve the model's performance, especially in identifying high-risk loans. Regular updates and refinements to the model can help enhance its predictive capabilities and mitigate financial risks associated with credit lending.

