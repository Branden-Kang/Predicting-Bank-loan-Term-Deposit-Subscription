# Predicting-Bank-loan-Term-Deposit-Subscription

## 1. Introduction
Theobjective is to increase prediction accuracy by finding the main factors that predict whether the client will subscribe a term. As our data are imbalanced, I use resampling methods before building prediction models. After preprocessing the data, I build models. The optimal model I get is the one using grid-search algorithm.
• Try to predict whether a bank client will subscribe a bank term deposit.
• Data preprocessing (checking the missing data and imbalanced data) and
conducted ExtraTree and XGBoost for feature selection
• Applied several Machine Learning algorithms (Logistic Regression, K means
Nearest, Decision Tree (Random Forest), SVM (Grid search), and Deep Neural
Network) to predict whether clients will subscribe the bank term deposit
• Obtained an optimal model with a remarkable 99% testing accuracy

## 2. Objective
The goal is to build a model to predict whether a client will subscribe. If the model has high prediction accuracy, I can arrange available resources to focus on the potential customers. In addition, I can choose out which variables are I plan to find out which factors has influence on the customers. That is, selecting important factors make good prediction and improve the profits efficiently.

## 3. Data Source
The data are related with bank deposit subscription for 40,181 clients and 15 features, and the decision variable (y) is whether the client subscribed a term.

## 4. Exploratory Data Analysis
4.1 Missing Data
The missing data can distort the real pattern hidden in the data. I looked into how many missing values are in each of these columns. After I check the dataset, there is no any explicit missing values for any variable. 

4.2 Converting Categorical Features
It is needed to convert categorical features to numerical features. Otherwise our machine learning algorithm won't be able to directly take in those features as inputs.

4.3 Imbalanced Data
The imbalanced data can blur the outcomes. In this case, the responses in the given dataset are about 90% for “0(No)” and 10% for “1(Yes)”.

4.4 Features Selection
Feature selection is a process where you select those features in your data that contribute most to the prediction variable or output in which you are interested. Three benefits of performing feature selection before modeling your data are: It reduces overfitting, improves accuracy, and reduces training time.

## 5. Methodology
Since this is a classification problem with binary response, the method I attempt to try includes logistic regression, k-nearest neighbors, decision tree (random forest), support vector machines (grid search) and neural network algorithms. All my models are supervised machine learning algorithms. I do not choose K means Clustering because all my data is labeled, unsupervised machine learning is not suitable and I can use supervised machine learning algorithms for this case.
