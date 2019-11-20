# Predicting-Bank-loan-Term-Deposit-Subscription

## 1. Introduction
Theobjective is to increase prediction accuracy by finding the main factors that predict whether the client will subscribe a term. As our data are imbalanced, we use resampling methods before building prediction models. After preprocessing the data, we build models. The optimal model we get is the one using grid-search algorithm.
• Try to predict whether a bank client will subscribe a bank term deposit.
• Data preprocessing (checking the missing data and imbalanced data) and
conducted ExtraTree and XGBoost for feature selection
• Applied several Machine Learning algorithms (Logistic Regression, K means
Nearest, Decision Tree (Random Forest), SVM (Grid search), and Deep Neural
Network) to predict whether clients will subscribe the bank term deposit
• Obtained an optimal model with a remarkable 99% testing accuracy

## 2. Objective
The goal is to build a model to predict whether a client will subscribe. If the model has high prediction accuracy, we can arrange available resources to focus on the potential customers. In addition, we can choose out which variables are we plan to find out which factors has influence on the customers. That is, selecting important factors make good prediction and improve the profits efficiently.

## 3. Data Source
The data are related with bank deposit subscription for 40,181 clients and 15 features, and the decision variable (y) is whether the client subscribed a term.

4. Exploratory Data Analysis
4.1 Missing Data
The missing data can distort the real pattern hidden in the data. I looked into how many missing values are in each of these columns. After we check the dataset, there is no any explicit missing values for any variable. 
