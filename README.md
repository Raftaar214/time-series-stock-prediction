Time-Series Stock Price Prediction

This project focuses on forecasting stock market closing prices using time-series analysis.
It includes data preprocessing, trend analysis, and ARIMA-based forecasting.
The project is built for learning, interviews, and portfolio demonstration.

1. Project Overview

Forecast future stock closing prices

Perform exploratory time-series analysis

Apply ARIMA model for forecasting

Visualize predictions vs actual values

More models such as LSTM and Prophet will be added later.
2. Project Structure
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
3. Dataset

Stock: Meta / Facebook (FB)

Data: Daily closing prices

File: data/raw/FB.csv4. Model Used

4. Model Used
ARIMA (AutoRegressive Integrated Moving Average)
Steps included:

1.Stationarity check (ADF test)

2.Log transformation

3.Differencing

4.ACF/PACF plots

5.ARIMA model training

6.Forecasting future values

Notebook available in:
notebooks/ARIMA_Forecasting.ipynb
