# Health Status Prediction using CatBoost

## Overview
This project builds a machine learning model to predict health status using a dataset of various lifestyle factors. The model is trained using CatBoost, a gradient boosting algorithm well-suited for categorical data. The pipeline includes data preprocessing, model training, evaluation, and visualization of decision boundaries.

## Features
- **Data Preprocessing:** Handles missing values and encodes categorical features.
- **Train-Test Split:** Divides data into training, validation, and test sets.
- **Model Training:** Uses CatBoostClassifier with hyperparameter tuning.
- **Performance Evaluation:** Computes accuracy for training, validation, and test sets.
- **Visualization:** Plots the decision boundary based on key features.

## Installation
Ensure you have Python installed, then install the required libraries:
```bash
pip install numpy pandas matplotlib seaborn catboost scikit-learn
```


## Data Description
The dataset contains lifestyle attributes such as:
- **Numerical Features:** Physical fitness, mindfulness, sleep hours, daily steps, daily calories.
- **Categorical Features:** Diet preference, career, gender, activity level.
- **Target Variable:** `is_healthy` (Binary classification: 0 or 1).

## Model Performance
After training, the model provides accuracy scores for training, validation, and test sets.

## Visualization
The decision boundary plot helps visualize how the model distinguishes health status based on physical fitness and mindfulness.


