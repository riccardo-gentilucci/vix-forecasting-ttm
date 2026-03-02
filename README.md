# VIX Forecasting using IBM Granite TTM

This project evaluates the performance of **Tiny Time Mixers (TTM)**, a SOTA Foundation Model from IBM Research, for predicting the Cboe Volatility Index (VIX).

### 🎯 Objective
Compare zero-shot forecasting capabilities across different horizons (P5 to P126) using a rolling-window backtesting approach.

### 🛠️ Key Technical Features
- **Model**: `ibm-granite/granite-timeseries-ttm-r2`.
- **Pipeline**: Automated ETL, TimeSeries Preprocessing (TSP), and de-scaling.
- **Evaluation**: Focused on Mean Squared Error (MSE) and Mean Absolute Error (MAE).

### 🚀 How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Run the backtest: `python src/main.py`
