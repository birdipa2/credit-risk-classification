# Module 12 Report

## Overview of the Analysis

* The purpose of this analysis was to develop machine learning models to predict loan default risk based on financial information. The data used in this analysis contained various financial variables, and the goal was to predict whether a loan would be classified as a default (1) or not (0).

* The key variable of interest was the loan_status, which had two distinct values: 0 (healthy loans) and 1 (loan defaults).

* The analysis went through the following stages of the machine learning process:

  * Data preprocessing: This involved loading the data, separating the features and target variable, and splitting the data into training and testing sets.
  * Model training and evaluation: Two machine learning models, namely Logistic Regression with Original Data and Logistic Regression with Resampled Data, were trained and evaluated using the training and testing sets. The models were evaluated based on accuracy, precision, recall, and F1-score.
  * Model comparison and selection: The performance of the models was compared, and the best-performing model was identified. The model with resampled data has better accuracy, the ability to minimize false positives and false negatives, and overall precision, F1 score and recall for both label 0 and label 1, making it more effective in predicting loan default risk.

## Results

Following are the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Logistic Regression Model with Original Data:
  * Balanced Accuracy Score: 0.944
  * Precision (class 0): 1.00
  * Precision (class 1): 0.87
  * Recall (class 0): 1.00
  * Recall (class 1): 0.89
  * F1-Score (class 0): 1.00
  * F1-Score (class 1): 0.88



* Logistic Regression Model with Resampled Data:
  * Balanced Accuracy Score: 0.994
  * Precision (class 0): 1.00
  * Precision (class 1): 0.84
  * Recall (class 0): 0.99
  * Recall (class 1): 0.99
  * F1-Score (class 0): 1.00
  * F1-Score (class 1): 0.91

## Summary

Based on the results of the analysis, both models performed well in predicting loan default risk. The Logistic Regression model with Original Data achieved a balanced accuracy score of 0.952, indicating good overall predictive performance. It showed high precision for class 0 (healthy loans) and class 1 (loan defaults), indicating a low false positive rate. The model also demonstrated reasonable recall for both classes.

The Logistic Regression model with Resampled Data, achieved a higher balanced accuracy score of 0.994. It showed high precision for class 0 and class 1, indicating low false positive rates. The model exhibited excellent recall for class 1, capturing the majority of actual loan defaults.

Considering the higher balanced accuracy score and better recall for loan defaults, the Logistic Regression model with Resampled Data is recommended for predicting loan default risk. However, it is important to consider other factors such as interpretability and computational resources when making a final decision.
