# Credit Risk Classification Report

## Overview of the Analysis

 The analysis aims to develop a credit risk classification model using logistic regression to predict loan risk based on financial information.

### Financial Information and Prediction Target

The dataset 'lending_data' comprised columns including loan size, interest rate, borrower income, debt to income ratio, number of accounts, derogatory marks, total debt, and loan status. The prediction target was the 'loan status' column, 
where '0' represents a low-risk loan and '1' indicates a high-risk loan.

### Stage Information
1. Data Preprocessing: Included handling missing values, scaling, and encoding categorical variables if present.
2. Feature Selection: Identifying key features contributing to loan risk prediction.
3. Model Development: Utilized logistic regression (sklearn.linear_model) with the solver argument set to 'lbfgs'. 
4. Evaluation Metrics: Focused on balanced accuracy, precision, and recall scores to assess model performance.


## Results

* Machine Learning Model 1:
  * Accuracy: 94%
  * low-risk Precision: 100%
  * high-risk Precision: 87%
  * Recall: 89 %


* Machine Learning Model 2:
  * Accuracy: 99%
  * low-risk Precision: 100%
  * high-risk Precision: 87%
  * Recall: 100 %

## Summary

The logistic regression model fitted with OverSampled data performed much better than the model fitted with imbalanced data. Largely component to the model generating a higher accuracy score and a higher recall, indicating that the model will make fewer mistakes when classifying high-risk loans.
