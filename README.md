# credit-risk-classifcation Report 

## Overview of the Analysis

In this Challenge, I used various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

* The purpose of this project was to train a model to detect high-risk and healthy loans.
* The provided information included loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory mark count, total debt and loan status. 
* I used the loan status as the training model predictor. 
* Split data into training and testing sets, checked balance of label variables by using value_counts, split data into training and testing datasets using train_test_split.
* I created a Logistic Regression Model using the original data and fit the model to predict loan status. I then checked the accuracy of test dataset- 99.2%

## Results


* Machine Learning Model:
  * Precision -- 100% accuracy Healthy Loans & 87% High Risk Loans
  * Recall -- 100% accuracy Healthy Loans & 89% High Risk Loans 
  * f1-score -- 100% accuracy Healthy Loans & 88% Hight Risk Loans

## Summary

In summary, I would recommend using this model to accurately identitfy healthy loans as it has shown a 100% accuaracy. High Risk Loans can be organized as "questionable" or "inconclusive" and will require further analysis. 

