# Credit-Risk-Classification Report


## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of this analysis was to develop a credit risk model to predict whether a loan applicant is likely to default on their payments or not based on their financial information. The loas would then be classified as high-risk loand or a healthy loan.


* Explain what financial information the data was on, and what you needed to predict.
The data was based on things like loan size, interest rate, income, debt-to-income ratio, number of accounts, and total debt. Based on this information, we were supposed to predict if the homeowner would default on their payments.. If an applicant defaults, the loan would then be classified as a high risk loan and vice versa.


* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
The varialbs model is trying to predict the loan status and what would they be classified as - high risk loan or healthy loan.


* Describe the stages of the machine learning process you went through as part of this analysis.
The machine learning process included things like cleaning the data, selecting x and y values, split testing, fiting the model and executing a test model to predict the accuracy of the model, which was 99% in this case.


* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
The logisticregression method helped in determining if the loan was classified as healthy loan or a high risk loan.



## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
   . Balanced Accuracy Score - 99%
   . Precision - 92%
   . Recall - 94%



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  . Balanced Accuracy Score - 99%
   . Precision - 92%
   . Recall - 99%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best? Machine Learning Model 2 seems to work better relatively because of slightly better recall score which is 99% for Model 2 (as compared to 94% for Model1)
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) Yes it does, predicting 1 or high-risk loan is more important over 0 or healthy loan as it could help banks make better mortgage deals with future clients.
