# Prediction-Machine-Learning-Models
Training and testing five different Statistical Learning Models to predict if loans will be paid (LendingClub data)

In this project, three years worth of data (2012, 2013, 2014) from Lending Club- the online platform for personal lending- are used to train and test five statistical learning algorithms: kNN, Logistic Regression, Rpart, decision tree, C5.0, and Random Forest. 
The goal is to predict if the loans will be paid or not. Every model is evaluated for accuracy, and the best model is selected to classify 10% of the loans made during 2015.

The original dataset is downloaded from the kaggle website, and contains 12 years worth of data on all the loans granted during that period of time. Each loan is described in terms of 151 features and a target variable.
The target variable is the loan_status, which has 7 different levels, but we are only interested in two of them, fully-paid and charged-off. We use these two levels to do binary classifications. We apply the five step learning process for each model. The training data is randomly selected and amounts to 75% of the whole dataset, and the testing data is made with the remaining 25%. The predictions are then compared to both the training and the testing datasets to assess the accuracy of each model and check for possible overfitting. Finally, the most accurate model is fit to the totality of the dataset for 2012-14, and then used to classify the loan status for 10% of all the loans granted in 2015.
