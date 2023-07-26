# credit-risk-classification


## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* We are attempting to generate a model to predict weather a loan is either a high-risk or a healthy loan
* The Data contains the following variables: loan size, interest rate, income, debt to income ratio, the number of accounts, and weather they had derogetory marks or not.
* Using the "value_counts()" function we can tell the data leans heavily toward the healthy loans.
* Firstly, the data was split into the features and labels, and then training and testing sets. Then the model was created and used the analyze and predict loan 'health'
* The model used was logistic regression, and was tested using an accuracy score, confusion matrix, and a classification report.

## Results

* Machine Learning Model:
  * The accuracy of this model was 95.2% , precision was 99%, and recall was also 99%.


## Summary

I would reccomend the use of this model due to its high accuracy, precision, and recall scores. This model also tends to classify more people as high risk who aren't, then classify people as healthy when they are high-risk; making this model good to use due to its 'Safe' mistakes.
