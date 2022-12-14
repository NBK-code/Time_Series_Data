Tips for Time Series

## Stationary Data
1. Mean is constant.
2. Standard Deviation is constant.
3. No seasonality or cyclicity.
4. Augmented Dickey-Fuller (ADF) test can be used to identify stationary data.
5. Non-stationary data can be converted into stationary data by differencing.

## EDA
1. Dealing with time series data involves a lot of data analysis.
2. Often it is better to index the dataframe with the time variable. Enables faster querying.
3. Lag plot helps to find out auto-correlation.
4. Autocorrelation plot also helps to analyze different cycles.

## Handling Missing Values
1. We cannot drop the data as we need to preserve the order of the data.
2. We cannot impute the missing values with global mean or median as the data may have a seasonality or cyclicity.
3. For imputation, one can use forward fill, backward fill, use rolling window average, or fill in with previous year's value.

## Traditional Methods for Time Series Forecasting
1. ARIMA
2. Prophet
3. Neural Prophet
4. Vector Autoregression

## Machine Learning Methods for Time Series Forecasting
1. Any regressor
2. RNNs, LSTMs, GRUs, 1d CNNs
