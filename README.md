# credit-risk-classification

In this assignment, we use machine learning to analyze a dataset of credit lending activity to build a model that can help determine the riskiness of credit lenders.

Analysis Overview

Factors observed:

- loan size
- interest rate
- debt to income ratio of borrower's income
- number of accounts the borrower held
- marks against the borrower
- total debt

Results

Logistic Regression Model 1:

- Precision: 93% (an average--in predicting low-risk loans, the model was 100% precise, however the model was only 87% precise in predicting high-risk loans)
- Accuracy: 94%
- Recall: 95% (an average--the model had 100% recall in predicting low-risk loans, but 89% recall in predicting high-risk loans)

Logistic Regression Model 2:

- Precision: 93% (an average--in predicting low-risk loans, the model was 100% precise, though the model was only 87% precise in predicting high-risk loans)
- Accuracy: 100%
- Recall: 100%

Summary

Logistic Regression Model 2 is less likely to predict false negative results. However, based on the confusion matrices for each model, Logistic Regression Model 2 predicted slightly more false positives (low-risk when the actual was high-risk).

If the goal of the model is to determine which factors result in high-risk loans, neither model scores are above 90% precision. Logistic Regression Model 2 had fewer false predictions of the testing data overall and would be the best model to use based on the high accuracy and the results of this model.
