# Time-Series-Forecasting-with-LSTM-and-ARIMA
MSML 602 Final Project 2023

Academic time-series forecasting project using historical META stock data from `yfinance`.

The notebook fetches recent stock-price data, preprocesses it into time-windowed sequences, trains an LSTM model with TensorFlow/Keras, and evaluates prediction quality using RMSE.

## Methods

- Pulled historical stock data with `yfinance`
- Prepared sequential input windows for LSTM forecasting
- Trained a TensorFlow/Keras LSTM model
- Compared predicted vs. actual price trends with matplotlib
- Evaluated performance with RMSE

## Results

- Train RMSE: 12.21
- Test RMSE: 10.68

## Tools

Python, yfinance, pandas, NumPy, matplotlib, TensorFlow/Keras, Google Colab

## Status

Course/academic project cleaned for portfolio review. This is a forecasting experiment, not a production trading system.
