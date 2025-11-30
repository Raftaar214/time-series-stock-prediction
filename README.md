📈 Time-Series Stock Price Prediction

A simple and clean project for forecasting stock market closing prices using time-series analysis.
Useful for learning, interviews, and portfolio demonstration.

📌 1. Project Overview

🔍 Explore historical stock prices

📉 Analyze trends and stationarity

🔢 Build ARIMA model for forecasting

📊 Visualize actual vs predicted values

More models (LSTM, Prophet) will be added soon.

📁 2. Project Structure
time-series-stock-prediction/
│
├── notebooks/
│     └── ARIMA_Forecasting.ipynb
│
├── data/
│     └── raw/
│          └── FB.csv
│
├── README.md
└── LICENSE

🗂️ 3. Dataset

Stock: Facebook / Meta (FB)

Type: Daily closing prices

Location: data/raw/FB.csv

🤖 4. Model Used — ARIMA

Steps performed:

🧪 ADF stationarity test

🔧 Log transformation

🔁 Differencing

📉 ACF / PACF analysis

⚙️ ARIMA model training

📈 Forecast visualization

Notebook:
notebooks/ARIMA_Forecasting.ipynb
