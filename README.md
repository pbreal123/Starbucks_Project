# Starbucks_Project
This repository contains the code and report for my Capstone Project as part of Udacity’s Data Scientist Nanodegree program. The project is based on the Starbucks Capstone Challenge, where we use simulated customer data from the Starbucks rewards mobile app to predict which offers will be effective for users.

## 1. Installations:
The project is developed in Python, utilizing Jupyter Notebook within the Anaconda environment. The key libraries and packages used include:

pandas, numpy for data manipulation and analysis
math, json for basic operations and data parsing
sklearn (for model training, preprocessing, and evaluation), including:
train_test_split, StandardScaler, PolynomialFeatures
DecisionTreeClassifier, RandomForestClassifier, GridSearchCV
mean_squared_error, classification_report
Ridge regression model from sklearn.linear_model
matplotlib for data visualization
time for tracking execution time
## 2. Project Overview:
This project addresses two primary questions using Starbucks app data:

What factors contribute to the effectiveness of an offer?
Can we predict, based on offer and customer data, whether an offer will be accepted?
The data provided includes user demographics, offer details, and transaction history for three types of offers: Buy One Get One Free (BOGO), Discount, and Informational (which simply delivers product information without any direct incentive).

To answer these questions, I built separate models for each offer type.

## BlogPost can be found here
https://medium.com/@pramodbhatreal123/predict-starbucks-offers-2c548a9cb716
## Summary of Results:
For the first question, I found that the length of time a customer has been a member (tenure) was the most influential factor across all models.
For the second question, my models achieved the following accuracies:
BOGO: 82.83%
Discount: 87.35%
Informational: 75.3%
Despite slightly lower performance for Informational offers, a 75% accuracy rate is likely acceptable in a business context, as there’s no direct cost associated with presenting informational offers.

## 3. Files:
The repository includes four files:

Starbucks Capstone Challenge - Using Starbucks app user data to predict effective offers.ipynb: The main notebook containing the analysis and modeling.
Data files: portfolio.json, profile.json, and transcript.json, which contain offer details, user profiles, and transaction records, respectively.
## 4. Licensing, Authors, and Acknowledgments:
The data used in this project was provided by Udacity for educational purposes.
