# 📈 Revenue Forecasting using Machine Learning

This project focuses on predicting future revenue using time-series features and machine learning models like Random Forest and XGBoost.

---

## 🚀 Project Overview

The goal is to forecast revenue for upcoming days based on historical sales data.  
We use feature engineering techniques like:

- Lag Features (previous day revenue)
- Rolling Mean (trend smoothing)
- Date-based features (day, month, etc.)

---

## 📊 Dataset

- Contains daily revenue data
- Preprocessed for time-series forecasting
- Missing values handled and sorted by date

---

## ⚙️ Features Used

- `lag_1`, `lag_2`, `lag_3`
- `rolling_mean_7`
- `day`, `month`, `weekday`

---

## 🧠 Models Used

- Random Forest Regressor
- XGBoost Regressor

---

## 📉 Model Performance

| Metric | Value |
|-------|------|
| MAE   | 22037 |
| R²    | 0.90  |

👉 Good fit, but still scope for improvement using better feature engineering.

---

## 🔮 Forecasting

- Predicts next **15–30 days revenue**
- Uses recursive forecasting (previous predictions as input)

---

## 📌 Key Learnings

- Lag features capture short-term patterns
- Rolling mean helps identify trend stability
- Tree models handle non-linear patterns better than linear regression

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Matplotlib

---

## 📂 Project Structure
