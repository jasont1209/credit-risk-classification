# credit-risk-classification
 
## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The purpose of this analysis is to train and evaluate a model that can identify the creditworthiness of borrowers.
The dataset used was historical lending activity from a peer-to peer lending services company. 
We are trying to predict healthy loans and high-risk loans.
The machine learning process we went through is splitting the data into training and testing sets, using "loan_status" column from the original dataset as y and using the remaining columns as X. the training and testing is done with train_test_split, then a logistic regression model is created using the training data, which we then generate a confusion matrix and a classification report. 

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1 with the Original Data:
    * Precision:
        * Healthy Loans:   1.00
        * High-Risk Loans: 0.85
    * Recall
        * Healthy Loans:   0.99
        * High-Risk Loans: 0.91
    

## Summary

The results show that the model is very good at predicting healthy loans, but less so at predicting high-risk loans, albiet still at a high precision of 85%. The model is also able to capture healthy loans and high-risk loans at a high rate of 99% and 91% respectively.

