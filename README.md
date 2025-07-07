# 23021578-Time-Series
# Oil Price Forecasting Using ARIMA & Prophet

This project performs time series analysis and forecasting on **Brent crude oil prices** using two prominent techniques: **ARIMA** and **Facebook Prophet**. The aim is to compare classical statistical and modern decomposable models for medium- to long-term forecasting accuracy.

---

## Project Structure
# Methods Used

- **Exploratory Data Analysis (EDA)**
  - Histogram, boxplots, yearly breakdown
- **Stationarity Testing**
  - Augmented Dickey-Fuller (ADF), ACF, PACF
- **ARIMA Modeling**
  - Full grid search over `(p,d,q)` using AIC
  - Residual diagnostics
- **Prophet Forecasting**
  - Multiplicative seasonality
  - Monthly seasonality + automatic changepoints
- **Forecast Comparison**
  - RMSE as evaluation metric
  - Forecasts plotted vs. actuals

  # Report
  It discusses model design, evaluation, EDA findings, and implications for financial forecasting.

