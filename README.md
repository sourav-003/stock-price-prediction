# 📈 Stock Price Prediction using ARIMA/SARIMA (Apple Inc.)

## 🧠 Project Overview

This project focuses on forecasting the **Volume of Apple Inc. stock trades** using **Time Series Forecasting models** like **ARIMA** and **SARIMA**. The dataset contains historical stock prices from the **NASDAQ exchange** for Apple between **2018 and 2019**. The objective is to apply statistical modeling techniques to predict future values and evaluate the models using **RMSE** and **MAPE**.

---

## 🔍 Problem Statement

In the world of data-driven finance, predicting future stock behavior such as opening/closing prices and trade volumes is of immense interest. This project aims to:
- Explore the historical stock data of Apple Inc.
- Build time series forecasting models
- Evaluate performance and accuracy
- Understand the impact of model parameters and exogenous variables on prediction

---

## ⚙️ Methods & Techniques Used

- **Exploratory Data Analysis (EDA)**
- **ARIMA** and **SARIMA** modeling
- **Hyperparameter tuning** for best (p, d, q) and seasonal (P, D, Q, s)
- Forecasting on test data
- Evaluation using:
  - 📉 **Root Mean Squared Error (RMSE)**
  - 📊 **Mean Absolute Percentage Error (MAPE)**

---

## 📁 Files Included

- `Stock Price Prediction-Updated.ipynb`: Full Jupyter notebook with code, modeling, and evaluation
- `AAPL.csv`: Dataset with Apple's stock prices from NASDAQ
- `README.md`: Project description and documentation

---

## 📌 Technologies Used

- Python (pandas, numpy, matplotlib, seaborn)
- `statsmodels` for ARIMA/SARIMA
- `scikit-learn` for evaluation metrics
- Jupyter Notebook

---

## 🏁 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sourav-003/stock-price-prediction.git
