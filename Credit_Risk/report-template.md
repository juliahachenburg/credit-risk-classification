# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis was to train and evaluate a model using a dataset containing lending activity, such that it would be able to identify the creditworthiness of borrowers.

The labels were created using loan status, which could be either healthy (0) or high risk (1), and the features were created using borrower income, debt to income, number of accounts, derogatory marks, and total debt. Then data was split into training and testing datasets. The logistic regression model was fit to the training data and the testing data was used to make predictions. Lastly, the model’s performance was evaluated using a classification report and confusion matrix. 

## Results

 * Accuracy: The accuracy score was 0.99, which means the model correctly predicted the creditworthiness 99% of the time.  

 * Precision: The precision score was 0.87, which means that of all the samples the model classified as high risk, 87% of them were actually high risk. 

 * Recall: The recall score was 0.89, which means that of all the actual high risk samples, 89% were correctly classified as high risk. 

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

Given that the machine learning has an accuracy score of 0.99, and relavitely high precision and recall scores, I would reccommend this model. The model did predict healthy loans better than high risk loans, but this might be a good thing so that those who do have healthy loans will not be mistakenly classified as high risk.
