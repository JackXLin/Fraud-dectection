# Credit Card Fraud Detection

## Overview
This project aims to detect potential credit card fraud using a Random Forest model, an ensemble learning method that combines multiple decision trees to improve predictive accuracy and control over-fitting.

## Objective
The objective of this project is to build a predictive model that can identify fraudulent credit card transactions with a high degree of accuracy, leveraging the robustness of Random Forest.

## Dataset
The dataset used in this project contains transactions made by credit cards, where each transaction is labelled as fraudulent or genuine.

## Methodology
- **Data Preprocessing**: The dataset is cleaned and preprocessed to handle missing values and categorical variables.
- **Feature Engineering**: New features are created to improve the model's predictive power.
- **Model Training**: A Random Forest model is used to train on the preprocessed data, consisting of many decision trees to produce a more generalised model.
- **Evaluation**: The model's performance is evaluated using metrics such as accuracy, precision, recall, and F1 score.

## Requirements
- Python 3.8+
- Pandas
- NumPy
- Scikit-learn
