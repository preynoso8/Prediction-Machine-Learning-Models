# Prediction-Machine-Learning-Models
Training and testing five different Statistical Learning Models to predict if loans will be paid (LendingClub data)
Abstract
The powerful prediction capabilities of Machine Learning algorithms are rapidly transforming the way data
driven decisions are made accross all industries. Day by day, more algorithms are developed and implemented,
and more knowdlege is aquired on different ways to interpret large amounts of data, and use these mechanisms
in all kinds of processes, most importantly, in all sorts of high-stakes human decision making. In this work,
three years worth of data (2012, 2013, 2014) from Lending Club, the online platform for personal lending and
borrowing, are used to train and test five statistical learning algorithms: kNN, Logistic Regression, Rpart
decision tree, C5.0, and Random Forest. The goal is to predict if the loans will be paid or not. Every model
will be evaluated for accuracy, and the best model will be used to classify 10% of the loans made during 2015.
Introduction
The original dataset is downloaded from the kaggle website, and contains 12 years worth of data on all the
loans granted during that period of time. Each loan is described in terms of 151 features and a target variable.
The target variable is the loan_status, which has 7 different levels, but we are only interested in two of them,
fully-paid and charged-off. We will use these two levels to do binary classifications. We will apply the five
step learning process to each model covered in this project. There will be a randomized
subsetting of the complete dataset into two datasets, one for training (75% of the dataset), and the other one
for testing (remaining 25% of the dataset). The predictions will be compared to both the train and the test
datasets to assess the accuracy of each model and check for possible overfitting. The most accurate model
will be fit to the totality of the dataset for 2012-14 and then used to classify the loan status for 10% of the
loans granted in 2015.
