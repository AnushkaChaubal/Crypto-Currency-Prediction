# Cryptocurrency Price Prediction with LSTM Model

This repository contains code for predicting cryptocurrency prices using Long Short-Term Memory (LSTM) models. The project fetches cryptocurrency data from CoinCap using HTTP Client, with a specific focus on Bitcoin. The LSTM model is engineered for Time Series Analysis, aiming to forecast Bitcoin prices accurately.

## Features
- Utilizes CoinCap API for cryptocurrency data retrieval.
- Develops an LSTM model tailored for Time Series Analysis.
- Achieves high prediction accuracy with a low Mean Absolute Error (MAE) of 0.0216.
- Forecasts Bitcoin prices for the next 10 days using the LSTM model.

## Requirements
- Python 3.x
- NumPy
- Pandas
- TensorFlow
- CoinCap API
- sklearn

## Installation
1. Clone the repository: `git clone https://github.com/AnushkaChaubal/Crypto-Currency-Prediction.git`
2. Install dependencies

## Usage
1. Run `fetch_data.ipynb` to fetch cryptocurrency data from CoinCap API.
2. Execute `crypto_lstm.ipynb` to train the LSTM model.
3. View the results and evaluation metrics.

