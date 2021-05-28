# Time Series Analysis

In this notebok I use both Time-Series and Linear Regression forecasting to determine whether or not there is any predictable behaviour in Dollar-Yen exchange rate futures.
For the time series analysis I completed the following 4 steps to predict the price and volatility over the next 5 days:
  1. Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
  2. Forecasting Returns using an ARMA Model.
  3. Forecasting the Settle Price using an ARIMA Model.
  4. Forecasting Volatility with GARCH.
---

## Technologies

This project is written in python and uses various libraries including: pandas, numpy, matplotlib, statsmodels, arch, and sklearn.

---

## Findings

I used the results of my analysis to answer the following questions (see notebooks for conclusions):

   *Based on your time series analysis, would you buy the yen now?*
    
   *Is the risk of the yen expected to increase or decrease?*
    
   *Based on the model evaluation, would you feel confident in using these models for trading?*
    
   *Does this model (linear regression) perform better or worse on out-of-sample data compared to in-sample data?*
