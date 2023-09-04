
## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

        The machine learning models that was used involved logistic regression with the original data and a resampled version. Both were compared by using the same csv file to do a credit risk evaluation. The csv file involved data that had loan_size, interest_rate, borrower_income, debt_to_income, num_of_accounts, derogatory_marks, total_debt, loan_status. Using these models help split the data into two types so that it easier to read when predicting outcomes. Once I retrieved the scores from the original data, I used the resampled data to eliminate bias and see if the logistic regression would be the same. This will ensure the accuracy is correct since its like a "double check" on the work I have done.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

        * Machine Learning Model 1:
         In the first model the scores were great. 
             - accuracy score was 99%
             - Precision score was 100% tracked for low credit risk and 85% tracked for high risk 
             - Recall scores show 99% were for low credit risk and 91% were for high risk


        * Machine Learning Model 2:
         In the second model the scores were great as well. 
             - accuracy score was 99%
             - Precision score was 100% tracked for low credit risk and 85% tracked for high risk 
             - Recall scores show 99% were for low credit risk and 91% were for high risk


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

           Both machine learning models performed equally. So I can't determine which performed better. Since our problem is a boolean related topic, it makes it easier to use these models. However if we were not determining low or high credit risk and were determining who should get a loan, then I think the performance of these models would change. Then we may see a different outcome between the two.
