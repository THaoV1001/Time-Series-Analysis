# Time-Series-Homework
Homework for Week 10: Time Series
Background
The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.
In this assignment, you will test the many time-series tools that you have learned in order to predict future movements in the value of the Japanese yen versus the U.S. dollar.
You will gain proficiency in the following tasks:

Time Series Forecasting
Linear Regression Modeling

Time-Series Forecasting
In this notebook, you will load historical Dollar-Yen exchange rate futures data and apply time series analysis and modeling to determine whether there is any predictable behavior.
Follow the steps outlined in the time-series starter notebook to complete the following:

Decomposition using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
Forecasting Returns using an ARMA Model.
Forecasting the Settle Price using an ARIMA Model.
Forecasting Volatility with GARCH.

Linear Regression Forecasting
In this notebook, you will build a Scikit-Learn linear regression model to predict Yen futures ("settle") returns with lagged Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).
Follow the steps outlined in the regression_analysis starter notebook to complete the following:

Data Preparation (Creating Returns and Lagged Returns and splitting the data into training and testing data)
Fitting a Linear Regression Model.
Making predictions using the testing data.
Out-of-sample performance.
In-sample performance.
