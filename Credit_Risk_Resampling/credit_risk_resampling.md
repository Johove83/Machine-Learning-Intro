# Credit Risk Resampling Report
### Johnathan Overton

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* The purpose of this analysis was to train and test Machine Learning algorithms to classify healthy loans from high-risk loans
* The financial information used was based off of the lending_data.csv with the following dimensions
  * loan size
  * interest rate
  * borrower income
  * debt to income ratio, number of accounts
  * derogatory remarks, total debt
  * loan status

* In this model, the prediction of four variables was of interest
  * balanced accuracy score
  * RandomOverSampler
  * LogisticRegression
  * classification report imbalanced
* Machine Learning process stages
  * Split the Data into Training and Testing Sets
  * Create a Logistic Regression Model with Original Data
  * Predict using Logistic Regression Model with Resampled Data


## Results

Description of classification reports

* Machine Learning Model 1:
  * Model 1 Accuracy, Precision, and Recall scores.
      * Accuracy  = 99.2%
      * Precision = 98.2%
      * Recall = 99.5%



* Machine Learning Model 2:
  * Model 2 Accuracy, Preicision, and Recall scores.
    * Accuracy = 99.4%
    * Precision = 100%
    * Recall = 99.4%

## Summary

While both Machine Learning models perform exceptionally well, the second model is found to be ideal as it outperforms the first model in both accuracy and precision while losing only a tenth of a percent point in recall.

It is of note that the second model remains consistent in accurately predicting, both, health and high-risk loans.

Therefore it is my recommendation to utilize the second model in credit risk prediction.
