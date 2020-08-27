## Problem Statement
Churn is a one of the biggest problem in the telecom industry. Research has shown that the average monthly churn rate among the top 4 wireless carriers in the US is 1.9% - 2%.

"Predict behavior to retain customers. You can analyze all relevant customer data and develop focused customer retention programs." [IBM Sample Data Sets]
## Data information

Each row represents a customer, each column contains customer’s attributes described on the column Metadata.

### The data set includes information about:
- Customers who left within the last month – the column is called Churn
- Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device   protection, tech support, and streaming TV and movies
- Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
- Demographic info about customers – gender, age range, and if they have partners and dependents

## Initial plan for data exploration
- Overview the data
- check datatypes of the features
- check null values and take action
- Feature Engineering (One-hot-encoding, skewness check)
- Data Exploration (Visual Analysis)

## Plan for ML model execution (KNN, Logistic Regression, RandomForest)
1. Hyperparameter tuning
2. ML algorithm fitting, prediction
3. Result assessment - confusition Matrix, ROC & Precesion/recall curves

## Summary & Key Findings
so far, Random Forest model performed well.

- KNN and Randomforest model predicted similar results
- RandomForest model preformed good in positive class prediction which is the main focus for this problem with very high recall score (specificity)
- our model has a 88% recall. In such problems, a good recall value is expected.
- Precision and Recall follows a trade-off, and you need to find a point where your recall, as well as your precision, is more than good but both can't increase simultaneously.
#### overall  86%  is a very good result

## Suggestions for next steps
 
- some feature could be more importanat and ignoring some will make better model
- For this backward feature selection would give better result.
