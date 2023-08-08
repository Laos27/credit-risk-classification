# Module 12 Report Template


## Overview of the Analysis

The purpose of this analysis is to build a model that can predict the creditworthiness of borrowers. This means a model that can predict if a loan will be healthy or it has a high risk of defaulting. 

The dataset to work with has some information such as: loan size, interest rates, borrowers income, debt to income, number of accounts, derogatory marks, total debt and the loan status (that will be the dependent variable that we will predict with the model).

The statistical method that was used to predict the outcomes from the data was Logistic Regression. 

The main steps to perform this analysis were:
* The data was split into training and testing datasets.
* Once the data was split, the model was trained with the train data to teach the model to recognise classification patterns.
* We then generated a confusion matrix to measure the effectiveness of our model.
* And finally, we printed the classification report for the model, where the evaluation metrics for the model were calculated.


## Results

Logistic Regression Model:
* Accuracy: 99% 
* Precision: 100 % for Healthy Loans
* Precision: 87 % for High-Risk Loans
* Recall: 100 % for Healthy Loans
* Recall: 89 % for High-Risk Loans


## Summary

The Logistic Regression model predicted the category of healthy loans with 100% precision and 100% recall, which means that every time the model predicted a healthy loan was a true positive.
On the other hand, the model predicted high-risk loans with a precision of 87% and a recall of 89%. 

It is important to notice that the actual occurrences (Support) for healthy loans is 18759, which is much higher than the actual occurrences for high-risk loans, which is 625. This could indicate if the model had more occurrences for high-risk loans could have learned more, and hence the precision and recall could increase.

Considering the 100% precision and recall for the healthy loans category - I would recommend this model to the company. It could be used considering that when the model does not predict a healthy loan is more likely this will be a high-risk one.




