Author: Jeff Gielniak
Date: 2025-04-23

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:
I built a model off a database of loan information.  The model uses the information in the database to train itself and attempt to predict if the loan is a healthy loan or a high risk loan.  The information used to predict this is borrower income, interest rate, loan size, debt to income ratio, the number of accounts the borrower has, if they have derogatory marks or not, and their total debt.  I was attempting to predict if a loan was high risk ('1' in the loam status column) or healthy ('0') using a Logistic Regression model.  

To achieve this, we split the data into training and testing data, created the Logistic Regression model and then evaluated it's performance using a Confusion Matrix and Classification Report

## Results
The model is extremely good at predicting healthy loans, with very few predictions in almost 19000 possibilities and essentially 99.9% accuracy.  The model is not as great, but still very good at predicting high risk loan at a rate of about 94%

## Summary

I would recommend using this model since the overall accuracy is extremely high. The only issue you could have with it is that it sometimes will predict a loan to be healthy, when it is in fact high risk (about 15% of the time)