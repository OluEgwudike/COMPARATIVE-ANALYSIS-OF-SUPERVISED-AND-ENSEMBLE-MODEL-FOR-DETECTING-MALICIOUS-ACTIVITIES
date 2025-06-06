### COMPARATIVE-ANALYSIS-OF-SUPERVISED-AND-ENSEMBLE-MODEL-FOR-DETECTING-MALICIOUS-ACTIVITIES IN CYBER SECURITY 

This project implements supervised machine learning model and ensemble model in detecting in malicious activities in cyber security. 

## Dataset Description 

# Source: 

I sourced this dataset from kaggle, it is publicly avaliable on the website. The dataset is gathered by researchers at the university of New South Wales ( UNSW) in 2015. 
https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15?select=UNSW_NB15_testing-set.csv 

the dataset contain train and test dataset. i concatinated both so as to have robust dataset 

# Size: 

Train: 82332 rows and 45 columns 

Test: 175341 rows and 45 columns ( Because of the same columns in train and test it makes it possible to concatinate). 

Total size after concatination: 257673 rows and 45 columns. 

## Exploratory Data Analysis 

i plotted some graphs in the project like ; 

1. i plotted a bar chart to show the distibution of service

2. i plotted a bar and pie chart to show the attack category

## Data Preprocessing 

1. i also applied label encoder to convert the target variable from categorical columns to numerical columns

After the pre-processing i splitted the total dataset into train (80%) and test (20%) so as to have majority for the train and smaller percentage to test the trained model

## Model Implemented 

The precison percentage is calculated based on the mean of malicious and normal attack

# 1. Logisitic Regression:( 0.70%)

precision: (65%)

recall: (57.5%)

f1- score: (56.5%)

# 2. Naive Bayes: (0.63%)

precision: (54%%)

recall: (53%)

f1- score: (52.5%)

# 3. K-nearest neighbor: (0.78%)

precision: (75.5%)

recall: (73%)

f1- score: (74%)

## Ensemble model 

# 1. Gradient boosting: (0.91%)

precision: (89.5%)

recall: (89%)

f1- score: (89%)

# 2. Bagging classifier: (0.96%)

precision: (96%)

recall: (96%)

f1- score: (95.5%)

# 3. Stacking classifier: (0.96%)

precision: (95.5%)

recall: (95.5%)

f1- score: (95.5%)

The results shows that ensemble models performs better than standalone supervised machine learning model, with Bagging and Stacking Classifier achieving the highest accuracy of 96%. In contrast, Naive Bayes had the lowest performance, possibly because it's a standalone model and does not have the ability to handle large dataset. 
