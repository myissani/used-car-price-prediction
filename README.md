# 🚗 Used Car Price Prediction (Kaggle S4E9)

A machine learning pipeline designed to predict used car prices using exploratory data analysis (EDA), feature engineering, and regression modeling.

---

## 📌 Project Overview
The goal of this project is to accurately estimate used car prices based on vehicle characteristics such as make, model, year, mileage, engine specs, transmission, and accident history.

- **Dataset:** [Kaggle Playground Series - Season 4, Episode 9](https://www.kaggle.com/competitions/playground-series-s4e9)
- **Target Variable:** `price` (Continuous)
- **Evaluation Metric:** Root Mean Squared Error (RMSE)

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python 🐍
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn`, `lightgbm`, `xgboost`

---

## 📊 Workflow & Methodology
1. **Exploratory Data Analysis (EDA):**
   - Visualized price distributions and target skewness.
   - Analyzed relationships between vehicle mileage, age, and resale value.
2. **Data Preprocessing & Cleaning:**
   - Handled missing values across categorical and numeric features.
   - Processed text/categorical features like `brand`, `model`, and `transmission`.
3. **Feature Engineering:**
   - Extracted car age from manufacture year.
   - Encoded high-cardinality categorical attributes.
4. **Model Training & Evaluation:**
   - Trained regression models (Linear Regression, Random Forest, LightGBM/XGBoost).
   - Evaluated model performance using validation metrics.

---

## 📁 Repository Structure
```text
├── playground_prediction.ipynb   # Main Jupyter notebook with code & visualizations
├── README.md                     # Project documentation
