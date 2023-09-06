# credit-risk-classification

## Background:

In this challenge, I used various techniques to train and evaluate a model based on loan risk. I used a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Results:

Machine Learning Model 1 - Logistic Regression:

Accuracy: 0.9442676901753825
Precision: 1.0 (healthy) / 0.87 (high risk)
Recall scores: 1.0 (healty) / 0.89 (high risk)

Machine Learning Model 2 - Logistic Regression With Resampled Data:

Accuracy: 0.994180571103648
Precision: 0.99 (healthy) / 0.99 (high risk)
Recall scores: 0.99 (healty) / 0.99 (high risk)

## Summary:

Precision results: Both maching learning modules produced strong favorable results when predicting the precision for healthy loans.  When reviewing the models for high-risk loans, the first model had a much lower rate then that of the module with the 'Resampled Data' (87% vs 99%).

Recall results:  Very similar to that of the Precision resutls, healthy loans had very positive results for both models, 100% and 99% respectively.  Regarding the Recall scores for high risk loans, there's a materia difference in results when comparing the initial model with a result of 89% vs that of the Resampled model with a very favorable result of 99%. 

Accuracy:  The overall accuracy for the Resampled Data had a much stronger result with 99% vs 94% for the original model.
To summarize, our model using the resampled data performs slightly better after comparing the accuracy score and classification report.

In summary, overall the model using the Resampled data has more favorable results, being consistent in all key measurements.  Whereas the initial model raises concerns on the effectiveness and the ability to properly assess risk for 'high risk' applications.  With the increase in sample data, we can predict risky loans vs healthy loans more precisely.  It appears the more the data is balanced, the more accurate the predictions are.
