# 📊 Crypto Price Prediction using XGBoost

This project uses machine learning (XGBoost Regressor) to predict cryptocurrency prices — including **Bitcoin (BTC)**, **Ethereum (ETH)**, and **Solana (SOL)** — based on historical price data and technical indicators.

---

## 🧠 Project Objectives

- Predict next-day closing prices for selected cryptocurrencies.
- Use historical price data from Yahoo Finance.
- Apply technical indicators like RSI, SMA, EMA, and volatility.
- Evaluate model performance using Mean Absolute Error (MAE).
- Easily switch between different coins using command-line arguments.

---

## 🏗️ Tech Stack

| Tool        | Purpose                        |
|-------------|--------------------------------|
| **Python**  | Programming language           |
| **XGBoost** | Gradient boosting model        |
| **Pandas**  | Data manipulation              |
| **NumPy**   | Numerical computation          |
| **Matplotlib** | Visualization               |
| **Scikit-learn** | Train/test split, metrics |
| **yfinance** | Crypto price data source      |

---

## 🗂️ Project Structure

crypto-price-prediction-xgboost/
│
├── data/ # (Optional) For saving CSVs if needed
├── crypto_price_predictor.py # Main training and prediction script
├── requirements.txt # Dependencies
└── README.md # Project documentation



---

## 📈 Features & Indicators

The model uses the following inputs:

- **Open, High, Low Prices**  
- **SMA_10**: 10-day Simple Moving Average  
- **EMA_10**: 10-day Exponential Moving Average  
- **RSI**: Relative Strength Index (momentum)  
- **Volatility**: 10-day rolling standard deviation  
- **Lag_1**: Previous day's close price  

---

## 🚀 How to Use

### ✅ 1. Clone the Repository

```bash
git clone https://github.com/fsaavedra0003/Crypto-Price-Prediction-Using-XGBoost
cd crypto-price-prediction-xgboost
