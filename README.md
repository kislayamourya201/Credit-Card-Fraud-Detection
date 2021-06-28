# Credit-Card-Fraud-Detection

### Dataset used:-
I have used dataset called creditcard_fraud available on Kaggle

## Context
- It is important that credit card companies are able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.
## Content
- The datasets contains transactions made by credit cards in September 2013 by european cardholders.
- This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions.
- The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
- It contains only numerical input variables which are the result of a PCA transformation.
- Unfortunately, due to confidentiality issues, we cannot provide the original features
- Features V1, V2, ... V28 are the principal components obtained with PCA
- The only features which have not been transformed with PCA are 'Time' and 'Amount'.
- Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset.
- The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning.
- Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Task
- Identify fraudulent credit card transactions.

## Concepts used:-
- Undersampling:
  - 1) Random undersampling
  - 2) Undersampling using Imblearn
  - 3) NearMiss
  
- Oversampling:
  - 1) Random oversampling
  - 2) Oversampling using Imblearn
  - 3) SMOTE(Synthetic Minority Oversampling)
  
- Models for anomaly detection:
  - 1) Local Outlier Factor(LOF) Algorithm
  - 2) Isolation Forest Algorithm 
