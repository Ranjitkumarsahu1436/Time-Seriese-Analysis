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
