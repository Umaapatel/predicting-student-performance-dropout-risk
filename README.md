# Predicting Student Performance and Dropout Risk

## Overview
This project uses machine learning techniques to analyze student academic and behavioral data. 
The goal is to predict final exam performance and identify students who may be at risk of dropping out.

## Dataset
- Student performance dataset with demographic, academic, and behavioral attributes
- Features include grades (G1, G2), study time, attendance, failures, and family support
- Target variables:
  - Final Grade (G3) – Regression
  - Dropout Risk (Yes/No) – Classification
## Data Dictionary (Key Variables)

The dataset contains student demographic, academic, behavioral, and support-related attributes.
Key variables include:

- **G1, G2** – First and second period grades
- **G3** – Final grade (target variable for regression)
- **studytime** – Weekly study time
- **failures** – Number of past failures
- **absences** – School absences
- **Dalc, Walc** – Alcohol consumption indicators
- **schoolsup, famsup** – Academic support indicators


## Machine Learning Models
- Linear Regression – Final grade prediction
- K-Nearest Neighbors (KNN) – Pass/Fail classification
- Naïve Bayes – Behavioral pattern classification
- Decision Tree (CART) – Dropout risk prediction

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib

## Evaluation Metrics
- Regression: RMSE, MAE, R²
- Classification: Accuracy, Precision, Recall, F1-score, Confusion Matrix

## Conclusion
This project demonstrates an end-to-end machine learning workflow including data preprocessing, model building, evaluation, and interpretation of results for real-world decision-making.

