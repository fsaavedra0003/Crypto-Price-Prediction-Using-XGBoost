# Crypto Price Prediction Using XGBoost

Predict next-day cryptocurrency closing prices using historical data from the free CoinGecko API and XGBoost regression.

---

## Project Overview

This project leverages historical crypto market data and technical indicators to forecast future prices. Using XGBoost, a powerful gradient boosting model, we predict the next day’s closing price for popular cryptocurrencies like Bitcoin and Ethereum.

---

## Features

- Fetches historical OHLC and volume data via CoinGecko API (no API key required)
- Calculates technical indicators (moving averages, RSI, MACD, etc.)
- Trains an XGBoost regression model to predict closing prices
- Evaluates predictions with RMSE and R² metrics
- Visualizes feature importance and prediction accuracy

---

## Installation

1. Clone this repo:

   ```bash
   git clone https://github.com/yourusername/crypto-price-prediction-xgboost.git
   cd crypto-price-prediction-xgboost
