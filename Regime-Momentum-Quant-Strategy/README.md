# 📊 Regime-Based Multi-Asset Quant Strategy

## 🚀 Overview
This project implements a quantitative investment strategy that dynamically allocates capital across asset classes using:

- 🌍 Macroeconomic regime detection 
- 📈 Momentum filtering 
- 🔁 Backtesting framework 

## 🧠 Strategy Logic
1. Detect market regime (Growth, Inflation, Crisis, Neutral)
2. Assign base asset weights based on regime
3. Apply momentum filter (only invest in assets with positive trend)
4. Rebalance portfolio dynamically

## 📊 Assets Used
- S&P 500
- NIFTY 50
- Gold
- Crude Oil

## ⚙️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- yfinance

## 📈 Performance
- Annual Return: ~27%
- Sharpe Ratio: ~1.3
- Max Drawdown: ~12%

## ⚠️ Notes
- Momentum is lagged to avoid look-ahead bias
- No transaction costs included
- Further improvements possible with ML-based regimes

## 🔮 Future Work
- Add transaction costs
- Walk-forward validation
- Machine learning regime detection

## 📁 File Structure
Regime-Momentum-Quant-Strategy/
│
├── quant_strategy.ipynb
├── README.md
├── requirements.txt
