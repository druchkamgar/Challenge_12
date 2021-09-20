# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
To train a supervised learning algo to predict credit risk of individuals.
* Explain what financial information the data was on, and what you needed to predict.
The supervised learning algo used 7 features, including: loan size, interest rate, income, debt to income, number of accounts, derogatory marks, and total debt; to predict loan status.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
There were roughly 77500 total accounts of which ~2500 were in danger of default.

* Describe the stages of the machine learning process you went through as part of this analysis.
We created test and training data sets to train a logistic regression model and make predictions. We then resampled the data to improve accuracy.

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).
We used logistic regression and resampling to improve predictive performance on the test data set to over 99%.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
Recall was 0.99 and 0.91 respectively. Accuracy was 95% and precision 99%.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
Recall was 99% for both groups, accuracy was 99% and precision was 99%.


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
The model that uses resampled data perfoms best, based on the metrics provided above.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
It is more important to predict the 1's than 0's in this analysis. The model trained on resampled data should be used.

If you do not recommend any of the models, please justify your reasoning.
