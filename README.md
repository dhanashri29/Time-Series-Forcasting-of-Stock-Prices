# 📈 Stock Price Forecasting using Time Series Analysis

This project uses **ARIMA, SARIMA, and Prophet** models to analyze and forecast stock prices.

## 🚀 Features
✅ Downloaded stock data using **yfinance**  
✅ Performed **Exploratory Data Analysis (EDA)**  
✅ Checked for **stationarity** (ADF test, differencing)  
✅ Built and compared **ARIMA, SARIMA, and Prophet models**  
✅ Evaluated performance using **MAE, RMSE**  

## 📊 Results
| Model   | MAE  | RMSE |
|---------|------|------|
| **ARIMA**  | 27.59 | 32.10 | 
| **SARIMA** | 31.89 | 36.72 | 
| **Prophet**| 15.73 | 18.11 | 

🚀 **Best Model:** Prophet

## 📂 Files
- `Time Series Forcasting of Stock Prices.ipynb` → Full analysis and forecasting code  
- `README.md` → Project documentation   

## 🔧 Installation
```bash
pip install yfinance pandas numpy matplotlib seaborn statsmodels fbprophet pmdarima
