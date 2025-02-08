# Module 20 Report

## Overview of the Analysis

The purpose of this analysis was to predict whether a loan is high-risk or healthy using historical data from a peer-to-peer lending platform. The dataset included financial information about borrowers, and the goal was to classify loans into two categories: healthy loans (0) and high-risk loans (1).

To complete the analysis, I followed these steps:

1) Prepared the data by splitting it into features (X) and labels (y), and then divided it into training and testing sets.

2) Trained the model using logistic regression, which is a common approach for binary classification problems like this.

3) Evaluated the model’s performance using a confusion matrix and metrics like accuracy, precision, recall, and F1-score.

## Results

* Logistic Regression Model:
    * Accuracy: 99%
    * Precision:
        * Healthy Loans (0): 100%
        * High-Risk Loans (1): 84%
    * Recall:
        * Healthy Loans (0): 99%
        * High-Risk Loans (1): 94%
    * F1-Score:
        * Healthy Loans (0): 100%
        * High-Risk Loans (1): 89%

* The confusion matrix shows:
    * True Positives (High-Risk Loans Predicted Correctly): 583
    * True Negatives (Healthy Loans Predicted Correctly): 18,655
    * False Positives (Healthy Loans Predicted as High-Risk): 110
    * False Negatives (High-Risk Loans Predicted as Healthy): 36


## Summary

The logistic regression model performed extremely well, with an accuracy of 99%. It’s highly effective at identifying healthy loans (0), with perfect precision and a recall of 99%. For high-risk loans (1), the recall is strong at 94%, which means the model successfully detects most of them. However, its precision for high-risk loans is 84%, meaning some healthy loans are flagged as high-risk.

## Recommendation 

The logistic regression model performed extremely well, with an accuracy of 99%. It’s highly effective at identifying healthy loans (0), with perfect precision and a recall of 99%. For high-risk loans (1), the recall is strong at 94%, which means the model successfully detects most of them. However, its precision for high-risk loans is 84%, meaning some healthy loans are flagged as high-risk.
