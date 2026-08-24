# TCS Stock Price Analysis and Forecasting Using ARIMA and LSTM

## 📌 Project Overview

This project analyzes historical TCS stock-market data and forecasts stock prices using two time-series models: **ARIMA** and **LSTM**.

The project follows an end-to-end data science workflow, including data collection, data cleaning, exploratory data analysis, visualization, time-series forecasting, model evaluation, and model comparison.

## 🎯 Objectives

- Analyze historical TCS stock prices.
- Perform exploratory data analysis.
- Visualize stock-price trends and moving averages.
- Forecast stock prices using ARIMA and LSTM.
- Compare model performance using MAE, MSE, and MAPE.

## 📊 Dataset

**Dataset Title:** TCS Historical Stock Market Dataset

The historical stock data was collected using the `yfinance` Python library.

- **Company:** Tata Consultancy Services (TCS)
- **Market:** NSE India
- **Ticker:** `TCS.NS`
- **Data Type:** Historical daily stock-market data

## 🤖 Models Used

- ARIMA
- LSTM (Long Short-Term Memory)

## 📈 Evaluation Metrics

- **MAE** – Mean Absolute Error
- **MSE** – Mean Squared Error
- **MAPE** – Mean Absolute Percentage Error

## 📊 Visualizations

- TCS closing-price trend
- 20-day moving average
- 50-day moving average
- Daily returns
- ARIMA actual vs predicted prices
- LSTM actual vs predicted prices
- ARIMA vs LSTM model comparison

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- yFinance
- Scikit-learn
- Statsmodels
- TensorFlow / Keras
- Joblib
- Jupyter Notebook

## 📁 Project Structure

```text
TCS-Stock-Price-Forecasting/
│
├── TCS_Stock_Analysis.ipynb
├── arima_tcs.pkl
├── lstm_tcs.keras
├── tcs_scaler.pkl
├── requirements.txt
└── README.md
