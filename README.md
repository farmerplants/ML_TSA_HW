# UMN Fintech -- Machine Learning &amp; Time Series Analysis Homework
## The solutions can be found in the Resources and Solutions folder:
#### Time Series Analysis: https://github.com/farmerplants/ML_TSA_HW/blob/main/Resources%20and%20Solutions/time_series_analysis.ipynb
#### Regression Analysis: https://github.com/farmerplants/ML_TSA_HW/blob/main/Resources%20and%20Solutions/regression_analysis.ipynb

## Homework Background:
### The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.
### In this assignment, you will test the many time-series tools that you have learned in order to predict future movements in the value of the Japanese yen versus the U.S. dollar.

## Homework Instructions:
### In the time_series_analysis notebook, you will load historical Dollar-Yen exchange rate futures data and apply time series analysis and modeling to determine whether there is any predictable behavior.
### Follow the steps outlined in the time-series starter notebook to complete the following:
#### - Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
#### - Forecasting Returns using an ARMA Model.
#### - Forecasting the Settle Price using an ARIMA Model.
#### - Forecasting Volatility with GARCH.
### Use the results of the time series analysis and modeling to answer the following questions:
#### - Based on your time series analysis, would you buy the yen now?
#### - Is the risk of the yen expected to increase or decrease?
#### - Based on the model evaluation, would you feel confident in using these models for trading?
### In the regression_analysis notebook, you will build a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with lagged Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).
### Follow the steps outlined in the regression_analysis starter notebook to complete the following:
#### - Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)
#### - Fitting a Linear Regression Model.
#### - Making predictions using the testing data.
#### - Out-of-sample performance.
#### - In-sample performance.
### Use the results of the linear regression analysis and modeling to answer the following question:
#### - Does this model perform better or worse on out-of-sample data compared to in-sample data?


## Conclusions:
### Time Series Analysis - Based on the models, I would not buy the yen now. While the price of the yen is looking to increase, as is the risk. The models above are mostly not good fits; the GARCH model is the best fit, however, there are only a few significant values. I would not feel confident using these models for trading.
### Regression Analysis - This model performs better on the out-of-sample over the in-sample data. In this case, the lin reg model was not good at predicting future performance.
