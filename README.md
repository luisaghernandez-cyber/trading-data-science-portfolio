# trading-data-science-portfolio
A beginner-friendly data science portfolio focused on Bitcoin market data. Includes data cleaning, exploratory analysis, technical indicators, visualizations, and simple machine learning models using Python.
#  Trading Data Science Portfolio  
A complete end-to-end data science workflow applied to trading:  
data cleaning, technical indicators, forecasting models, and backtesting strategies.

# Repository Structure
---

#  1. Data Cleaning & Preprocessing  
_Notebook: `1_data_cleaning.ipynb`_

This notebook performs:

- Load raw OHLCV data  
- Fix mislabeled headers  
- Convert string dates → datetime  
- Convert numeric columns to proper types  
- Handle missing values  
- Set `Date` as index  
- Produce a clean, analysis-ready time series  

---

#  2. Technical Indicators  
_Notebook: `2_technical_indicators.ipynb`_

Technical indicators calculated:

- SMA20 / SMA50  
- EMA  
- RSI  
- MACD  
- Historical volatility  

These indicators serve as features for trading signals and strategy design.

---

#  3. ARIMA Forecasting  
_Notebook: `3_arima_forecast.ipynb`_

This notebook:

- Splits data into train/test  
- Fits an ARIMA model  
- Forecasts BTC/USD prices  
- Plots predictions vs actual values  
- Calculates:

  - MAE  
  - MSE  
  - RMSE  

This provides a baseline statistical forecast for financial time series.

---

#  4. Backtesting Trading Strategies  
_Notebook: `4_backtesting_strategies.ipynb`_

Strategies implemented:

### 1️ Buy & Hold (benchmark)

### 2️ Golden Cross Strategy (SMA20 > SMA50)

### 3️ RSI Contrarian Strategy  
- Buy when RSI < 30  
- Exit when RSI > 70  

### Performance Metrics  
- CAGR  
- Volatility  
- Sharpe Ratio  
- Max Drawdown  
- Cumulative return curves  

---

# How to Run

### Option A — Google Colab
1. Upload notebooks  
2. Upload dataset `btc_usd.csv`  
3. Run cells sequentially  

### Option B — Local Environment

Install: pip install pandas numpy matplotlib statsmodels scikit-learn
Clone repo:git clone https://github.com/
<your-username>/trading-data-science-portfolio.git
cd trading-data-science-portfolio

Run via Jupyter or VSCode.

---

#  Contact

**Luisa Gabriela Hernández Laverde**  
Bogotá, Colombia  
Email: luisaghernandez@gmail.com  

---

# Future Improvements

- LSTM / deep learning forecasting  
- GARCH volatility models  
- Portfolio optimization  
- Reinforcement-learning trading agents  



