# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis was to predict a customer's credit worthiness for a loan based off of the loan amount, interest rates, the borrower's income, debt to income ratio, number of accounts, number of derogatory marks, and their total debt. This model was created practice machine learning skills to predict whether a loan will default or not. The stages of the machine learning process I went through as part of this analysis are as follows: Step 1: Load the CSV data into a dataframe. Step 2: Create the features and the labels datasets for the x and y values. Step 3: Split those datasets into training and testing datasets. Step 4: Use the training data to create a logistic regression model Step 5: Review the predictions from the test data Step 6: Evaluate the model's performance. Logistic Regression was again used with the "oversampled" data and an accuracy score, confusion matrix and classification report produced for comparison with the previous data for model 2.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy: .99
  * Precision: Healthy-1.00 Unhealthy-.85
  * Recall: Healthy-.99 Unhealthy-.91

* Machine Learning Model 2:
  * Accuracy: .99
  * Precision: Healthy-1.00 Unhealthy-.84
  * Recall: Healthy-.99 Unhealthy-.99

## Summary

In summary, both models have  a .99 Accuracy. The only slight difference is the recall in model 2 is higher than in model 1. I do not have a recommendation for what model I believe to be better.
