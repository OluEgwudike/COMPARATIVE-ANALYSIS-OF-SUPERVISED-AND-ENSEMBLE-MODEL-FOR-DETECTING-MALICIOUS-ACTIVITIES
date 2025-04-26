### COMPARATIVE-ANALYSIS-OF-SUPERVISED-AND-ENSEMBLE-MODEL-FOR-DETECTING-MALICIOUS-ACTIVITIES IN CYBER SECURITY 

This project implements supervised machine learning model and ensemble model in detecting in malicious in cyber security. 

## Dataset Description 

# Source: 

I source this dataset from kaggle, it is publicly avaliable on the website. the dataset is gathered by researchers at the university of New South Wales ( UNSW) in 2015. 

the dataset contain train and test dataset. i concatinated both of them so has to have robust dataset 

# Size: 

Train: 82332 rows and 45 columns 

Test: 175341 rows and 45 columns ( Because of the same columns in train and test it makes it possible to concatinate). 

Total size after concatination: 257673 rows and 45 columns. 

## Exploratory Data Analysis 

i plotted some graphs in the project like ; 

1. i plotted a bar chart to show the distibution of service

2. i plotted a bar and pie chart to show the attack category

## Data Preprocessing 

1. i concatinated both the train and test to have a robust dataset.

2. i also applied label encoder to convert the target variable from categorical columns to numerical columns

After the pre-processing i splitted the total dataset into train (80%) and test (20%) so as to have majority for the train and smaller percentage to test the trained model

## Model Implemented 

# 1. Logisitic Regression:( 0.70%)

precision: ( 65%)

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

