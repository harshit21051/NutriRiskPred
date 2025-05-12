# NutriRiskPred

**NutriRiskPred** is a machine learning project that predicts the probabilistic risk of multiple diseases based on the nutritional content of food items. The project uses a multi-output regression approach with models like XGBoost and Scikit-learn regressors to estimate disease risk percentages for 50+ food attributes.

## 🔍 Overview

This project focuses on public health and nutrition analysis using data science. Given a food item's nutrient profile and category, the model outputs estimated probabilities for risks of diseases such as hypertension, diabetes, and more.

## 🧠 Techniques Used

- Multi-output regression using **XGBoost**
- **Feature engineering** from structured and unstructured nutritional data
- Disease probability extraction using **regex parsing**
- Preprocessing via **StandardScaler** and one-hot encoding

## 📊 Data Preparation

- Parsed a column containing disease names and their probability ranges (e.g., "Diabetes (10-20%)") into separate numeric targets.
- Created threshold columns and structured outputs for multi-target regression.
- One-hot encoded food categories and normalized features.

## 🏗️ Models and Evaluation

- Implemented XGBoostRegressor for multi-output predictions.
- Performed hyperparameter tuning to optimize model performance.
- Achieved strong predictive accuracy on test data.

## 🛠️ Dependencies

- Python 3.9+
- pandas
- scikit-learn
- xgboost
- openpyxl

Install them via:

```bash
pip install pandas scikit-learn xgboost openpyxl