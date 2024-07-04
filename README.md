# Credit Card Fraud Detection Using Logistic Regression
### Overview <br>
This project aims to detect fraudulent credit card transactions using a logistic regression model. The dataset used for this project is highly imbalanced, with a small percentage of fraudulent transactions compared to non-fraudulent ones. The goal is to create a model that can accurately identify fraudulent transactions while minimizing false positives.

### Dataset <br>
The dataset used for this project is the Credit Card Fraud Detection dataset from Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders. It includes 284,807 transactions, of which 492 are fraudulent. The dataset is highly imbalanced, with the positive class (frauds) accounting for 0.172% of all transactions.
### Features <br>
The dataset contains the following columns:

1)Time: Number of seconds elapsed between this transaction and the first transaction in the dataset.<br>
2)V1 to V28: Principal components obtained with PCA (to protect confidentiality).<br>
3)Amount: Transaction amount.<br>
4)Class: Target variable (1 for fraudulent transactions, 0 for non-fraudulent transactions).<br>
