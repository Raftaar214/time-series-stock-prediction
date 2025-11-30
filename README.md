📘 Time-Series Stock Price Prediction

A complete time-series forecasting project that analyzes and predicts stock market prices using classical statistical models (ARIMA) and advanced deep learning models (LSTM). This project is structured for interviews, portfolio showcase, and real-world ML workflow demonstration.

📌 1. Project Overview

The goal of this project is to forecast future stock prices using multiple time-series techniques.
The project demonstrates:

Data cleaning & preprocessing

Trend, seasonality & stationarity analysis

Classical forecasting (ARIMA)

Deep learning forecasting (LSTM — coming next)

Model evaluation & comparison

Forecast visualization

This project reflects end-to-end ML pipeline skills used in data science interviews.

📂 2. Project Structure
time-series-stock-prediction/
│
├─ notebooks/
│    ├─ ARIMA_Forecasting.ipynb
│    ├─ (LSTM_Forecasting.ipynb — coming next)
│    └─ (Prophet_Forecasting.ipynb — optional)
│
├─ data/
│    └─ raw/
│         └─ FB.csv
│
├─ src/
│    └─ (future scripts: preprocessing, models, training)
│
├─ README.md
└─ LICENSE


This folder design is industry standard and looks very professional during interviews.

📊 3. Dataset

Ticker used: Meta/Facebook (FB)

Source: Extracted manually (or via yfinance in future versions)

Columns used: Date, Close

Range: Daily stock prices

Dataset is stored in:

data/raw/FB.csv

🔧 4. Technologies & Libraries Used
Python

pandas

numpy

matplotlib

statsmodels (ARIMA)

sklearn (metrics)

Deep Learning (upcoming)

TensorFlow / Keras OR PyTorch (for LSTM)

Prophet (upcoming)

prophet by Meta

📈 5. Methods Implemented
✔ ARIMA (AutoRegressive Integrated Moving Average)

Steps performed:

Stationarity testing (ADF test)

Rolling mean & variance analysis

Log transform

Differencing

ACF & PACF plots

ARIMA model fitting

Forecasting future values

Visualizing actual vs predicted prices

This notebook is already uploaded:

notebooks/ARIMA_Forecasting.ipynb

🤖 6. Upcoming Enhancements (Interview-Strong Additions)
🔜 LSTM Model

Sequence-to-sequence prediction

Sliding window dataset creation

Train/test split

Model training & evaluation

Plot: Actual vs Predicted

🔜 Prophet Model

Trend + seasonality + holidays

Automatic change-point detection

🔜 Model Comparison

RMSE

MSE

MAPE

Graph comparison

These upgrades will make the project very strong for interviews.

📉 7. Results So Far

ARIMA successfully fits log-scaled series

Early forecasting accuracy is acceptable

Visualization shows meaningful prediction behavior

More accurate results expected after adding LSTM
