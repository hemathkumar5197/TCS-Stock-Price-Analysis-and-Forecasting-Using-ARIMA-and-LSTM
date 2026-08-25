# TCS Stock Price Analysis and Forecasting Using ARIMA and LSTM

## 📌 Project Overview

This project focuses on analyzing historical **Tata Consultancy Services (TCS)** stock-market data and forecasting stock prices using two time-series forecasting models: **ARIMA** and **LSTM (Long Short-Term Memory)**.

The project follows an end-to-end data science workflow, including data collection, data preprocessing, exploratory data analysis (EDA), visualization, time-series forecasting, model evaluation, model comparison, and next-day price prediction.

## 🎯 Objectives

- Analyze historical TCS stock-market data.
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA).
- Analyze stock-price trends and daily returns.
- Calculate and visualize 20-day and 50-day moving averages.
- Forecast TCS stock prices using ARIMA and LSTM.
- Evaluate model performance using MAE, MSE, and MAPE.
- Compare the performance of ARIMA and LSTM.
- Generate next-day stock-price predictions.

## 📊 Dataset

### Dataset Title

**TCS Historical Stock Market Dataset**

### Dataset Details

- **Company:** Tata Consultancy Services (TCS)
- **Market:** NSE India
- **Ticker:** `TCS.NS`
- **Data Type:** Historical daily stock-market data
- **Data Source:** Yahoo Finance
- **Data Collection Library:** `yfinance`

The dataset contains historical stock-market information used for time-series analysis and forecasting.

## 🔍 Data Analysis

The following analysis was performed on the TCS stock data:

- Dataset inspection
- Missing-value checking
- Data cleaning
- Statistical summary
- Closing-price analysis
- Daily return calculation
- 20-day moving average
- 50-day moving average
- Stock-price trend visualization
- Time-series analysis

## 📈 Exploratory Data Analysis

The project includes visualizations for:

- TCS historical closing prices
- 20-day moving average
- 50-day moving average
- Daily returns
- Stock-price trends
- Actual vs predicted prices

## 🤖 Models Used

### 1. ARIMA

**ARIMA (Autoregressive Integrated Moving Average)** is a statistical time-series forecasting model used to analyze historical patterns and forecast future stock prices.

### 2. LSTM

**LSTM (Long Short-Term Memory)** is a recurrent neural network designed to learn patterns and dependencies in sequential and time-series data.

LSTM is used to capture complex patterns in historical TCS stock prices.

## 📊 Evaluation Metrics

The models are evaluated using:

### MAE – Mean Absolute Error

Measures the average absolute difference between actual and predicted prices.

### MSE – Mean Squared Error

Measures the average squared difference between actual and predicted prices and gives greater weight to larger errors.

### MAPE – Mean Absolute Percentage Error

Measures the average prediction error as a percentage of the actual price.

**Lower error values indicate better forecasting performance.**

## 📊 Model Comparison

The performance of ARIMA and LSTM is compared using:

- MAE
- MSE
- MAPE

Based on the test results obtained in this project, **LSTM achieved lower error values than ARIMA**, indicating better forecasting performance on the selected TCS test dataset.

## 🔮 Prediction

The project generates:

- ARIMA next-day predicted price
- LSTM next-day predicted price

The final predictions are presented in a comparison table.

## 📊 Visualizations

The project includes:

- TCS Closing Price Trend
- 20-Day Moving Average
- 50-Day Moving Average
- Daily Returns
- ARIMA Actual vs Predicted Prices
- LSTM Actual vs Predicted Prices
- ARIMA vs LSTM Performance Comparison

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

## 👨‍💻 Author

**Hemanth Kumar N**

Aspiring AI/ML Engineer | Data Science Enthusiast | Python Developer

## 📁 Project Structure

```text
TCS-Stock-Price-Forecasting/
│
├── TCS_Historical_Stock_Data.csv
├── TCS_Stock_Analysis.ipynb
├── arima_tcs.pkl
├── lstm_tcs.keras
├── tcs_scaler.pkl
├── requirements.txt
├── README.md
