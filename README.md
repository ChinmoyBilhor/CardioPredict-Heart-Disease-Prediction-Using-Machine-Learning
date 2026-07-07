# ❤️ CardioPredict: Heart Disease Prediction Using Machine Learning

## Overview

CardioPredict is a machine learning project designed to predict the presence of heart disease using clinical patient data. The project demonstrates a complete machine learning pipeline, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and comparative performance evaluation. Three ensemble learning algorithms—Random Forest, XGBoost, and CatBoost—are implemented and compared to identify the best-performing model.

## Dataset

**Source:** Kaggle – Heart Disease Dataset

**Dataset Link:** https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data

### Features

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting Electrocardiographic (ECG) Results
* Maximum Heart Rate Achieved
* Exercise-Induced Angina
* ST Depression (Oldpeak)
* Slope of the Peak Exercise ST Segment

### Target

* **0** – No Heart Disease
* **1** – Heart Disease

## Technologies Used

* Python
* OS (Python Standard Library)
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost
* CatBoost
* KaggleHub

## Project Workflow

* Dataset Download and Exploration
* Data Inspection and Missing Value Analysis
* Feature Selection
* Missing Value Imputation
* Target Variable Transformation
* Exploratory Data Analysis (EDA)
* Categorical Feature Encoding
* Train-Test Split
* Feature Scaling
* Model Training
* Model Evaluation
* Comparative Performance Analysis

## Models Implemented

* Random Forest Classifier
* XGBoost Classifier
* CatBoost Classifier

## Model Configuration

### Random Forest

* Number of Trees: 100
* Random State: 42

### XGBoost

* Number of Estimators: 100
* Learning Rate: 0.1
* Maximum Depth: 3
* Tree Method: Histogram-Based
* Evaluation Metric: Log Loss
* Random State: 42

### CatBoost

* Iterations: 100
* Learning Rate: 0.1
* Task Type: GPU
* Random State: 42

## Evaluation Metrics

The models are evaluated using the following performance metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

## Performance Summary

| Model             |   Accuracy |  Precision |     Recall |   F1-Score |
| ----------------- | ---------: | ---------: | ---------: | ---------: |
| **Random Forest** | **85.87%** | **83.93%** | **92.16%** | **87.85%** |
| **XGBoost**       |     83.15% |     83.18% |     87.25% |     85.17% |
| **CatBoost**      |     80.43% |     80.56% |     85.29% |     82.86% |

**Best Performing Model:** Random Forest

## Project Files

* **CardioPredict_Heart_Disease_Prediction_Using_Machine_Learning.ipynb** – Complete project notebook
* **README.md** – Project documentation
* **requirements.txt** – Python dependencies

## Future Improvements

* Perform hyperparameter tuning using GridSearchCV or RandomizedSearchCV.
* Apply k-fold cross-validation for more robust model evaluation.
* Compare additional machine learning models such as LightGBM and Support Vector Machines.
* Perform ROC-AUC analysis and precision-recall evaluation.
* Visualize feature importance and explain predictions using SHAP.
* Deploy the trained model as an interactive web application using Streamlit or Flask.

## Author

**Chinmoy Bilhor**
