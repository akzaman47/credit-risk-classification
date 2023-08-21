# credit-risk-classification

use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

An overview of the analysis: We are using a trained model to predict risks in loans.
- The logisitic regression model has an accuracy of 99%, which I found to be good.
- Healthy Loans have a very good accruate prediction, which I would recommend doing.
- The high risk can be very cautious. The recall is at 84% while the support is at 91%

   precision    recall  f1-score   support

  healthy loans       1.00      0.99      1.00     18765
high-Risk loans       0.84      0.99      0.91       619

       accuracy                           0.99     19384
      macro avg       0.92      0.99      0.95     19384
   weighted avg       0.99      0.99      0.99     19384

A summary: I would recommend this model, due to the fact that the healthy loans are prediected accurately. High risk loans are high risk loans for a reason, the model does a good enough job to predict.
