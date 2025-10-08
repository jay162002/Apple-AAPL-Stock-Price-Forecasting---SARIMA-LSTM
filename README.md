# Apple (AAPL) Stock Price Forecasting - SARIMA & LSTM

This repo forecasts **Apple (AAPL)** stock prices using classic time-series methods (ARIMA/SARIMAX) and a lightweight **LSTM** baseline.  

It includes:
- Exploratory analysis (trend/seasonality, ACF/PACF, decomposition)
- Stationarity testing (ADF) and differencing
- SARIMA model selection via grid search (AIC/RMSE)
- A small LSTM model for comparison
- Visualizations and short-horizon forecasts


## Main Results 
- **ARIMA**: suggested differencing **d = 1**; best non-seasonal order found **ARIMA(1,1,1)**  
  - Validation **RMSE = 4.91**
- **LSTM** (10 epochs): **RMSE = 6.09**



