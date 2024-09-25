# Crime Prediction through Data Analysis and Statistical Learning

## Project Overview

This project aims to develop machine learning models to predict the occurrence of crimes based on a variety of factors such as location, time, and socioeconomic conditions. By analyzing historical crime data, the models can help law enforcement agencies identify potential crime hotspots and improve crime prevention efforts.

### Problem Statement

Criminal activity affects the quality of life and economic growth in many regions. The goal is to predict the occurrence of crimes in specific locations and time periods using machine learning algorithms, including Random Forest, Decision Trees, and Logistic Regression.

### Objectives
1. Develop models to predict where and when crimes are likely to occur.
2. Analyze the relationship between socioeconomic factors and crime rates.
3. Help law enforcement agencies allocate resources more efficiently and reduce crime rates.

## Dataset

- **Source:** [Kaggle Crime Dataset](https://www.kaggle.com/datasets/asaniczka/crimes-in-los-angeles-2020-2023)
- **Data Size (after cleaning):** 20MB with approximately 20,000 records.
- **Data Attributes:** Crime type, location, time, victim demographics, weapons used.

## Methodology

### Algorithms Used:
1. **Decision Trees:** Splits data based on feature values for easy interpretability but prone to overfitting.
2. **Random Forest:** An ensemble of decision trees to improve robustness and reduce overfitting.
3. **Logistic Regression:** Used for binary classification to predict the probability of crime occurrence.

### Data Preprocessing:
- Removed duplicate and null rows.
- Addressed class imbalance using random undersampling.
- Performed feature selection to boost model accuracy.

### Model Evaluation:
- Evaluated using accuracy, precision, recall, and F1-score.
- Best-performing model: **Random Forest**.

## Visualizations
- **Heatmaps:** Display crime occurrences based on type and location.
- **Feature Importance Plots:** Identify the most influential features.
- **Confusion Matrices:** Evaluate the performance of each model.

## Results
The **Random Forest Classifier** performed best in predicting crime occurrences. Visualizations provided insights into crime patterns, and the models can be used by law enforcement to optimize resource allocation.
