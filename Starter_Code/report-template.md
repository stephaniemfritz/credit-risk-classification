# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of the analysis is to confirm that the created model works well.
* Explain what financial information the data was on, and what you needed to predict.
I needed to predict whether the loan was healthy or high risk based upon loan_size	interest_rate	borrower_income	debt_to_income	num_of_accounts	derogatory_marks	total_debt
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
There were 77536 of each value.
* Describe the stages of the machine learning process you went through as part of this analysis.
I split the columns into features and labels. Then I split the data into a training and test set.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
I used Logistic regression as a model. I then made a confusion matrix and classification report.
## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
        The accuracy, precision, and recall scores are all pretty high. The accuracy, overall percentage of predictions that are correct. It is 99%. The precision is true positive predictions divided by the sum of the true positive predictions and false positive predictions. It is 99%. Recall is the true positive predictions divided by the sum of the true positive and false negative predictions. It is 99%.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best? I would recommend the logistic regression model. It performs very well.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
Performance is stil good even with the macro average, so it does not really matter.

If you do not recommend any of the models, please justify your reasoning.
