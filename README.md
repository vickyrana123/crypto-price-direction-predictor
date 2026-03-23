# 🪙 Crypto Price Direction Predictor (BTC/USDT)

A machine learning pipeline that predicts Bitcoin price direction 
(UP/DOWN) 15 minutes ahead using real-time Binance data.

## 🔍 Features
- Real-time data fetch from Binance public API (no API key needed)
- 40+ engineered features (RSI, Bollinger Bands, VWAP, EMA, Volume, Multi-timeframe)
- 5 models compared: Logistic Regression, Random Forest, Gradient Boosting, XGBoost, LightGBM
- Realistic backtesting with transaction costs & slippage
- RSI + VWAP rule optimization via grid search
- Live real-time prediction cell

## 🚀 Setup
```bash
pip install -r requirements.txt
```

## ▶️ Run
Open `crypto_prediction_optimized.ipynb` in Jupyter and run all cells.
> ⚠️ Requires live internet connection to fetch data from Binance.

## 📁 Project Structure
```
├── crypto_prediction_optimized.ipynb  # Main notebook
├── requirements.txt                   # Dependencies
├── README.md                          # Project documentation
└── Plot_Images/                       # Auto-created on run
```
