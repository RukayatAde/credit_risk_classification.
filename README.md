# credit_risk_classification.

**Instructions** :
The instructions for this Challenge are divided into the following subsections:

Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets
Open the starter code notebook and use it to complete the following steps:

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.


**NOTE**
A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting.

Split the data into training and testing datasets by using train_test_split.

Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Generate a confusion matrix.

print the classification report.



**Question** : How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

**Answer** :
**For Logistic Regression Model with the Original Data**

The prediction for healthy loan is 100% as the precision is the same with the actual one. But there is slight difference between the predicted high risk loan and the actual, as the actual is 89% while the precision is 87%.

The accuracy score is 99%.


**For Logistic Regression Model with the resampled Data**

The precision for the healthy loan is 1.00, this shows 100% accuracy of the predicted healthy loan

And the precision for the high risk loan is 0.87, showing 87% accuracy of the predicted high risk loan

The accuracy score is 100%, showing perfect prediction of this model.
