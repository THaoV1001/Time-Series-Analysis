# Time-Series

The financial departments of large companies often deal with foreign currency transactions while doing international business. As a result, they are always looking for anything that can help them better understand the future direction and risk of various currencies. Hedge funds, too, are keenly interested in anything that will give them a consistent edge in predicting currency movements.

In this project, many time-series tools that are used to predict the future movements between the value of the Japanese yen versus the U.S. dollar.
Including

Time Series Forecasting
Linear Regression Modeling

Time-Series Forecasting
Gather historical Dollar-Yen exchange rate futures data and apply time series analysis and modeling to determine whether there is any predictable behavior.
Decompose data using a Hodrick-Prescott Filter (Decompose the Settle price into trend and noise).
Forecast Returns using an ARMA Model.
Forecast Settle Price using an ARIMA Model.
Forecast Volatility with GARCH.

Linear Regression Forecasting
a Scikit-Learn linear regression model is used to predict Yen futures ("settle") returns with lagged Yen futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).
Prepare data, train and fit a Linear Regression Model.
Make predictions using the testing data.
Analyse Out-of-sample performance.
Analyse In-sample performance.
