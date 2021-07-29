# KPMG-Forage-Internship

## Overview
Sprocket Central Pty Ltd needs help with its customer and transactions data. 
The organisation has a large dataset relating to its customers, but their team is unsure how to effectively analyse it to help optimise its marketing strategy.
<br> Build a model to predict which customers they should target

## Data
1. Customer Demographic 
2. Customer Addresses
3. Transactions data in the past 3 months

The three datasets are to be merged into one for exploratory data analysis and model development.
<br> The dataset is highly imbalanced as the cancelled orders are less than ten percent of the entire dataset. 
<br> Hence, SMOTE oversampling will be used to balance the dataset.

## Libraries and Packages Used
1. Python
2. Numpy Library
3. Pandas Library
4. Matplotlib Library
5. Seaborn Library
6. Scikit-learn Library

## Model Performance
1. Logistic Regression has an overall accuracy of 0.57.
2. Bagging classifier has an overall accuracy of 0.98.
3. Random Forest classifier(n_estimators = 850) with has an overall accuracy of 0.99, which is the highest performing model.
4. Naive Bayes has an overall accuracy of 0.57.
5. Support Vector Machine has an overall accuracy of 0.51.

## API Development
