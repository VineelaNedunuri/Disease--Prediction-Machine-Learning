# Disease-Prediction-Machine-Learning

For disease prediction here we are considering a Cardiovascular Disease dataset from kaggle.
The cardiovascular dataset is a collection of medical data related to patients with cardiovascular diseases and the data contains several features such as age, sex, blood pressure, cholesterol levels, glucose levels, smoking habits,weight, height and other details which causes risk of cardiovascular disease. This dataset consists of 70 000 records of patients data with 11 features and a target(cardio: Yes or No).

1. [Introduction](#Introduction)
2. [Exploratory Data Analysis (EDA)](#)
3. [Choosing Models](#)
4. [Prediction on Models](#)
5. [Evaluation of Models](#)
6. [Deployment](#)
7. [Conclusion](#)

---
## Introduction

The main aim of the project is to build a machine learning model that can predict the risk of cardiovascular disease based on several features.
 Machine learning algorithms can be trained on this dataset to identify the patterns and relationships between the various features and the risk of heart disease. By predicting the risk of heart disease accurately then healthcare professionals can provide personalized care to patients at high risk, which makes a better healthcare.

## Exploratory Data Analysis (EDA)
The dataset was cleaned and preprocessed to remove missing values and outliers of features. Features were engineered to improve the performance of the model. The data was visualized using plots to understand the distribution of the each feature.

## Choosing Models
Logistic Regression,KNN,Decision Tree, Random Forest, and Gaussian NB were chosen as the models to be trained on the two datasets

## Prediction on Models
Data was splitting into training, validation and testing set which was scaled with feature Standardization and Normalization.We define a hyperparameters of each model using GridSearchCV with their appropriate evaluation metric, fitting the models, and making predictions on the validation set.

## Evaluation of Models
Evaluate the performance of the models using confusion matrix and classification report. This should include a comparison of the performance of the different models and the reasons for choosing the final model.

## Model Deployment 

## Conclusion 

References:https://www.kaggle.com/datasets/sulianova/cardiovascular-disease-dataset 
