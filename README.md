# Interactive ML Decision Support System

This repository contains an end-to-end Machine Learning pipeline that culminates in an interactive web-based dashboard. The project evaluates student academic success and graduate admission probabilities using both classical models and advanced gradient boosting techniques.

## Interactive Dashboard Application
The core highlight is a **Dash (Plotly)** web application (`Dashboard_3.ipynb`) designed for decision-makers.
- **Dynamic Model Selection:** Toggle between multiple models (Logistic Regression, Random Forest, etc.) to compare results in real-time.
- **Hyperparameter Transparency:** Displays the exact tuned parameters resulting from GridSearchCV.
- **Forecasting Table:** A specialized "Disagreement Table" that sorts predictions by error count, allowing users to focus on high-risk or ambiguous student profiles.
- **Performance Tab:** Visualizes Accuracy and Confusion Matrices after 5-fold cross-validation.

## Project Components

### 1. Advanced Classification (`assignment2_classification.ipynb`)
- **Algorithms:** Logistic Regression, Decision Trees, SVM, KNN, and **CatBoost**.
- **Optimization:** Heavy use of `GridSearchCV` for hyperparameter tuning.
- **Key Insight:** Compares "Base" models against "Optimized" models to demonstrate the value of tuning.
- **Result:** Achieved high-precision classification of student pass/fail status using ensemble methods.

### 2. Admission Regression (`assignment2_regression.ipynb`)
- **Objective:** Predicting admission probability with high confidence.
- **Analysis:** Comparative study of regression metrics (R², MSE, MAE).
- **Visualization:** Includes parity plots and top-3 model comparison bar charts.

## Tech Stack
- **Dashboarding:** Dash, Plotly, HTML/CSS.
- **Machine Learning:** Scikit-Learn, CatBoost.
- **Data Engineering:** Pandas, NumPy, OpenPyXL (for Excel integration).
- **Environment:** Designed for Google Colab and local Jupyter environments.
