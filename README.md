**Credit-Card-Fraud-Detection**

This is a machine learning project made on Credit Card Fraud Detection. The data is taken from Kaggle. Different classification machine learning algorithms have been applied to get the maximum accuracy.

**About Project**

The purpose of the project is to make a machine learning model that will be able to detect whether the transaction made is fraud or genuine based upoen the given parameters. 
The parameters used to calculate the whether the class is fraud or genuine, we are not given any information regarding the features of the dataset in order to maintain the privacy of the user.

**Dataset Link**

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

**About The Dataset**

This dataset contains transactions made by credit cards in September 2013 by European cardholders. 
This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. 
Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. 
Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. 
Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. 
The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-sensitive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.
