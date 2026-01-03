# Stock Price Forecasting using Time Series Models

## 📌 Overview
This project provides a universal framework for forecasting stock prices using classical
time series models. It is designed to work with **any stock market dataset** that contains
historical price information.

## 🗂 Dataset
- Source: Yahoo Finance (or similar financial data providers)
- Required columns:
  - Date
  - Closing Price

> Note: Tesla stock data was used as a sample dataset for experimentation, but the
> framework is applicable to any publicly traded stock.

## 🧠 Models Implemented
- **Prophet**
  - Used as a baseline model for trend and seasonality analysis
- **ARIMA**
  - Statistical time series model applied after handling non-stationarity

## ⚙ Methodology
- Data preprocessing and visualization
- Train-test split (80–20)
- Stationarity testing using ADF test
- Differencing for ARIMA modeling
- Forecasting and model evaluation

## 📊 Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## 📈 Results & Observations
- Prophet captures long-term trends but performs poorly on highly volatile financial data
- ARIMA shows improved short-term forecasting capability after differencing
- Classical models struggle with sudden market regime changes

## 🛠 Tools & Libraries
- Python
- Pandas, NumPy
- Matplotlib
- Prophet
- Statsmodels
- Scikit-learn

## 🚀 Future Improvements
- Predict returns instead of raw prices
- Add LSTM-based deep learning models
- Integrate technical indicators
- Build a real-time forecasting dashboard using Streamlit

## 📎 Disclaimer
This project is for educational and research purposes only and should not be used for
financial trading or investment decisions.
