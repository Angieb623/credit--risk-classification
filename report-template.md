# Module 20 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Purpose of the analysis: The purpose of this analysis is to predict and identify the creditworthiness of borrowers using the Logistic Regression machine learning module.

* Financial information data needed to predict: The financial information data was a large dataset of loans that was used to predict based on the loans' status. All other information was used to train the data.

* Variables used to predict (e.g., `value_counts`). The value_counts variable counted the values of each loan type (healhty and high-risk). The balance_accuracy variable is used to measure the average accuracy of the imbalanced data.

* Stages of the machine learning process: 
  *Import file and create into a Dataframe
  
  *Split the data into training and testing sets by its' features and labels to use for predicting and training. 

  *Use train_test_split for testing and training the data.

  *Create a Logistic Regression Model by importing SKLearn.

  *Created an instance of the model and fit the mode to make predictions from the test data.

  *Created a classification_report to evaluate the predictions and accuracy by using a confusion matrix. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model: Logistic Regression
  * Healthy Loan Scores:
    * Precision: 100%
    * Recall: 99%
    * F1-score: 100%
    * Accuracy: Ranged from 92% - 95%

  * High-Riak Loan Scores:
    * Precision: 85%
    * Recall: 91%
    * F1-score: 88%
    * Accuracy: 99%


## Summary

Per the classification report, the model predicted the healthy loans at a slightly lower accuracy than with the high-risk loans. The accuracy scores could be off due to the fact that there are over 18,000 healthy loans versus the high-risk loans only having 619. Therefore, there could be either false positives or false negatives for either loan label, which could skew the calucations.

The precision, recall, and f1-score were predicted at 100% and 99% values. Overall, the model did good with its' predictions.

I recommend this model as it aides in the predictions of future loans based on the loans features.
