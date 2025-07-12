# Task 2: Stock Price Prediction (AAPL & TSLA)

## 🔹 Objective:
Predict the next-day stock closing prices using past data for Apple (AAPL) and Tesla (TSLA) separately to compare performance and trends.

## 📊 Dataset:
- **Source**: Yahoo Finance (`yfinance` library)
- **Stocks Used**: 
  - Apple Inc. (`AAPL`)
  - Tesla Inc. (`TSLA`)
- **Date Range**: 2024 to 2025

## 🧠 Model Applied:
- Linear Regression

## ⚙️ Workflow:
1. Fetched real-time historical data using `yfinance`
2. Created a `Target` column (next day’s price)
3. Split data into training and testing sets
4. Trained and evaluated a linear regression model

## 📌 Key Results:
- Visualized actual vs predicted prices for both AAPL and TSLA
- Observed daily trend alignment and prediction accuracy
- A simple model for short-term forecasting using only the 'Close' price

## 📦 Dependencies:
```bash
pip install yfinance pandas matplotlib scikit-learn
