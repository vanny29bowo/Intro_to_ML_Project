# Predicting Airline Passenger Satisfaction with Classification Algorithms

## Introduction
This project aims to utilize machine learning algorithm for helping companies focusing on objectives below:

1. Predicting airline passenger satisfaction (satisfied or dissatisfied), that focusing on dissatisfied passenger because We want to earlier anomaly of Customer that potentially stop using the service.
2. Focusing on the most important factors that leads to passenger satisfaction and passenger dissatisfaction for gaining insight on product service improvement.
The machine learning algorithm that will be used in this project are K-NN, Logistic Regression and Decision Tree.

## Datasets
The dataset sourced from Kaggle has 103904 entries and 25 features. Below the detail description of each features. The data was proceed on Google Collab and using Python code followed by several libraries from it. Each of data processing such as Exploratory Data Analysis (EDA), pre-processing, modelling and calculating certain values from formulas the data will be copied on separated variables for maintaining data authenticity. For output variable, the category “neutral or dissatisfied” will be set as positive class(1) and category “satisfied” will be set as negative class(0).

## Modelling
On modelling process, used three different machine learning algorithms as comparative analysis to create models, that were Logistic Regression, K-Nearest Neighbors and Decision Tree. Let’s discussion the concept fundamental of each algorithms

## Evaluation
There are several evaluation metrics on supervised classification, but on this learning experiment will be used accuracy, precision, recall and F1-score as indicator of model’s performance with recall as main score because back to main objective of this project, we want to earlier detect anomaly of Customer that potentially will churn with decrease amount of false negative.

## Conclusion
From all models on this experiment, start from Logistic Regression, K-Nearest Neighbors and Decision Tree, obtained the best model with the highest score is Decision Tree algorithm model with score on testing data precision:0.95, recall:0.95, accuracy:0.97, and F1: 0.96. Decision Tree works very well on classification problem with mechanism splitting data based on elements of the feature that contain most information recursively with construct the tree form. But can be led to overfitting when max_depth of tree get into deep, but can handle with hyperparameter tuning to solve this anomaly.
