# Credit Risk Classification (Supervised Machine Learning Model)
## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    * The purpose of this analysis is to build a model that can identify the creditworthiness of borrowers.

* Explain what financial information the data was on, and what you needed to predict.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
   * Dependant variable (y value) in this analysis was the "loan status" indicating if a loan is healthy or at risk.
    Independent Variables (x values) were loan size, interest rate, borrower income, debt to income ratio, number of accounts and derogatory marks.

* Describe the stages of the machine learning process you went through as part of this analysis.
   * In this analysis, we first split our data to traning and test sets. Then, define our dependent and independent variables. Next, we create logistic regression model and fit our original data to this model. Trained model is used to make predictions. Lastly, we evaluate the model`s performance.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
    * Two diffeent Logistic Regression models were created by using the original data set and randomy over resampled data set (to get rid of the imbalances). In the end, their results were gathered with scikit-learn library.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:

  * Accuracy :  0.99 
  * Precision:  1.00 (For Healthy Loan),  0.85(High Risk Loan)
  * Recall : 0.99(For Healthy Loan), 0.91(High Risk Loan)


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
    * Only Logistic Regression model was used and it seems to perform very good at predicting healthy loan but not very good at predicting high risk loan. Because we have lot more of examples of low risk people versus examples of high risk people. 


* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
  * Logistic Regression model  predicts '0' lot better than it predicts '1'




