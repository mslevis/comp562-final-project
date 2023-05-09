# Predicting Credit Risk with Machine Learning Models

</br>

COMP 562 Spring 2023 Final Project

By Owen Tan, Rena Pei Qi Chong, Ming Feng Chua, Alissa

[Project Report](https://github.com/mslevis/comp562-final-project/blob/master/COMP562_Credit_Risk_Prediction.pdf)

## Motivation
Credit risk assessment has always been a vital part of the work of financial institutions. It is imperative for them to determine each individual's credit risk accurately to reduce the risk of defaulting on each credit that they gave. While traditional credit risk assessment exists, machine learning models are now more used in the industry because their prediction is more accurate.

## Dataset
[German Credit Risk Dataset](https://www.kaggle.com/datasets/uciml/german-credit)

Our dataset consists of real-life individual data from Germany who took a loan and their credit risk (good or bad). There are 10
features in the data: age, sex, job, housing, saving accounts,
checking account, credit amount, duration, and purpose. We use all of the
features to determine whether a person has a
good or bad credit risk in our machine learning model.


## Ideas
We first cleaned the data and preprocessed all of the categorical data with one-hot encoding. We then used the sci-kit library to do: Decision Trees, Random Forest, Logistic Regression, and Naive Bayes. After tuning the hyperparameters, we evaluated all 4 models and concluded that logistic regression and decision trees perform the best in predicting the credit risk of individuals. 
