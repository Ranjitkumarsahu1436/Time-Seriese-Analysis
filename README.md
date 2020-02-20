# Time-Seriese-Analysis

Time Series is a sequence of well-defined data points measured at consistent time intervals over a period of time.Time series analysis is the use of statistical methods to analyze time series data and extract meaningful statistics and characteristics about the data.

# why we are useing Time Seriese analysis
Time series analysis is use in order to understand the underlying structure and function that produce the observations. Understanding the mechanisms of a time series allows a model to be developed that explains the data in such a way that prediction, monitoring, or control can occur.

# Introduction to ARIMA Models
So what exactly is an ARIMA model?

ARIMA, short for ‘Auto Regressive Integrated Moving Average’ is actually a class of models that ‘explains’ a given time series based on its own past values, that is, its own lags and the lagged forecast errors, so that equation can be used to forecast future values.

Any ‘non-seasonal’ time series that exhibits patterns and is not a random white noise can be modeled with ARIMA models.

An ARIMA model is characterized by 3 terms: p, d, q

where,

p is the order of the AR term

q is the order of the MA term

d is the number of differencing required to make the time series stationary

If a time series, has seasonal patterns, then you need to add seasonal terms and it becomes SARIMA, short for ‘Seasonal ARIMA’. More on that once we finish ARIMA.


Term ‘Auto Regressive’ in ARIMA means it is a linear regression model that uses its own lags as predictors. Linear regression models, as you know, work best when the predictors are not correlated and are independent of each other.

# Autocorrelation
Informally, autocorrelation is the similarity between observations as a function of the time lag between them.

# Seasonality
Seasonality refers to periodic fluctuations. For example, electricity consumption is high during the day and low during night, or online sales increase during Christmas before slowing down again.

# Stationarity
Stationarity is an important characteristic of time series. A time series is said to be stationary if its statistical properties do not change over time. In other words, it has constant mean and variance, and covariance is independent of time.
