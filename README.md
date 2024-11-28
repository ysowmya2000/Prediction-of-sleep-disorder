# Sleep Disorder Prediction using Machine Learning
This repository contains a machine learning project aimed at predicting sleep disorders based on various health and lifestyle factors. The dataset was sourced from Kaggle and includes features such as Sleep Quality, Stress Level, BMI, Blood Pressure, and more. By analyzing these factors, the project identifies individuals at risk of sleep disorders and provides insights into their key contributors.
## Project Overview
The goal of this project is to analyze the factors affecting sleep health and predict potential sleep disorders. Through Exploratory Data Analysis (EDA) and the implementation of machine learning models, we derive insights into sleep health and predict sleep disorder types based on individual data.
## Methodology
### Data Preprocessing
1. Filled null values.
2. Cleaned and prepared data for analysis.
### Data Splitting
Dataset was divided into training and testing sets in a 3:1 ratio.
## Machine Learning Models Used
Logistic Classification
K-Nearest Neighbors (KNN) Classifier
Random Forest Classifier
## Evaluation Metrics
Accuracy
Recall
Precision
F1-Score
## Model Performance
1. Random Forest Classifier: 89% accuracy
2. KNN Classifier:	88% accuracy	
3. Logistic Regression Classifier: 87% accuracy

The Random Forest Classifier was the best-performing model, achieving an accuracy of 89%.

Based on the Random Forest model, the top three features influencing predictions are:
Blood Pressure,
BMI Category,
Age.

## Dataset: https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset 
## Conclusion
The project successfully predicts sleep disorders with a high degree of accuracy. The Random Forest Classifier was identified as the best model, achieving an accuracy of 89%. The analysis highlights significant contributors such as Blood Pressure, BMI, and Age, offering actionable insights for improving sleep health.
