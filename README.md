# Project-6
Final Project Proposal

# Title: What makes us happier?

Introduction

In this project I am going to use the World Happiness Report dataset from Kaggle.com and I am going to analyze how variables such as life expectancy, gdp per capita, corruption, and others affect the overall happiness of people within different countries. The data used in the dataset contains information collected  from survey based research where respondents responded to main life evaluation questions and ranked their current lives on the scale of zero to ten. They ranked the best possible life for them as a 10 and the worst possible life as a 0. I have data from 2015 to 2022, but I plan to compare the data from two years only. One before Covid-19 pandemic and one year during the Covid-19 pandemic to analyze how Covid-19 also affected the level of happiness in different countries. The original dataset has more variables than I intend to use, so I am going to clean the data and remain with few independent features: GDP per capita, life expectancy, and Government corruption, and freedom. 

I believe that I have good data, but not 100% accurate respective to years. In some cases where countries are missing one or more happiness factors over the survey period, information from earlier years is used as if they were current information. This may cause some bias in my results but it will not make a huge difference. There is a limit of 3 years for how far back the researchers went in search of those missing values.

To complete my final project, I am going to follow the following steps.

Step 1

I am going to install all scipy libraries that I will be using in my analysis. I plan to use scipy, numpy, matplotlib, pandas, and sklearn. 
  
Step 2

In addition to installing scipy libraries, I will also import other libraries that I will use. These libraries will include decision tree classifier, train_test_split, KNeighborClassifir, Gaussian NB, StratifieldKfold, and others. 
  
Step3

After importing all important libraries, I will import my dataset in google colab and start checking the dimensions of my data and check statistical summaries to have the idea of the data I am working with. 
  
Step 4 

I am going to separate my data into test and train data sets and I will set up a 10-fold cross validation and build other models to compare the predictions and select the best model. I am trying to compare Logistic Regression, Gaussian Naive Bayes, SVM, Locally weighted regressor, xgboost, and others in order to find which one gives the best predictions for my data.
  
Step 5 

I will select the best model and make predictions and evaluate them by comparing them to expected results in the test set. I will also calculate the confusion matrix to know the accuracy of the best performing model. Throughout the project, I will be using different visualizations like multivariate plots to present the results of different models and best performing model as well. 

