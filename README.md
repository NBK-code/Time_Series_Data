#Tips for Time Series
### EDA
1. Dealing with time series data involves a lot of data analysis.
2. Often it is better to index the dataframe with the time variable. Enables faster querying.
3. Lag plot helps to find out auto-correlation.
4. Autocorrelation plot also helps to analyze different cycles.

### Handling Missing Values
1. We cannot drop the data as we need to preserve the order of the data.
2. We cannot impute the missing values with global mean or median as the data may have a seasonality or cyclicity.
3. For imputation, one can use forward fill, backward fill, use rolling window average, or fill in with previous year's value.
