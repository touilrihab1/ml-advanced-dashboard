# ML Advanced Dashboard Project

This project demonstrates an end-to-end supervised machine learning workflow with **interactive dashboards**.  
It focuses on regression and classification tasks using public datasets, showcasing model comparison, hyperparameter tuning, cross-validation, and visualization.

---

## Notebooks

1. **Regression Notebook**  
   - Dataset: Public regression dataset (e.g., Boston Housing, California Housing, or similar)  
   - Models used:
     - Random Forest Regressor
     - XGBoost Regressor
     - CatBoost Regressor
     - LightGBM Regressor
   - Steps:
     - Data preprocessing and scaling
     - Model training and evaluation
     - Hyperparameter optimization with GridSearchCV
     - K-fold cross-validation
     - Comparison with previous models (optional)
     - Visualizations: Parity plots, error histograms, performance bar charts

2. **Classification Notebook**  
   - Dataset: Public classification dataset (e.g., Titanic Survival, Iris, or similar)  
   - Models used:
     - Random Forest Classifier
     - XGBoost Classifier
     - CatBoost Classifier
     - LightGBM Classifier
   - Steps:
     - Data preprocessing and scaling
     - Model training and evaluation
     - Hyperparameter optimization with GridSearchCV
     - K-fold cross-validation
     - Performance comparison
     - Visualizations: Confusion matrices, accuracy bar charts, model comparison plots

---

## Dashboard

The dashboard is built with **Dash + Plotly** and visualizes:
- Top 3 best-performing models
- Hyperparameters of selected models
- Performance metrics (R², MSE, RMSE, MAE for regression; Accuracy for classification)
- Predictions vs. true values for selected observations
- Interactive controls:
  - Dropdown / Radio buttons to select models
  - Multiple checkboxes to select performance metrics
  - Tabs to navigate between data overview, performance metrics, predictions, and parity plots

---

## Technologies & Libraries

- Python 3.x  
- Pandas, NumPy  
- Scikit-learn, XGBoost, CatBoost, LightGBM  
- Plotly, Dash  
- Matplotlib, Seaborn  

---

## How to Run

1. Open notebooks in **Google Colab** or **Jupyter Notebook**.
2. Install required libraries (if needed):
```bash
pip install numpy pandas scikit-learn matplotlib seaborn plotly dash xgboost catboost lightgbm
