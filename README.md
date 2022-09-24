# stock_predictor

## This criterion is linked to a Learning OutcomeAlgorithm Understanding

- How does the Prophet Algorithm differ from an LSTM?

The difference lies in the handling of seasonalities. The LSTM prediction is based on the last set of values and less prone to the variance due to seasonality. The prophet model finds out and displays seasonalities. Prophet has also been specifically designed to detect patterns in business time series. LSTM models though are a more powerful approach to learning from sequential data. 

- Why does an LSTM have poor performance against ARIMA and Prophet for Time Series?

The LSTM model is more prone to overfitting as reported by neptune.ai, as through there evaluations determined that the LSTM is too advanced for rather small datasets when compared to Prophet and ARIMA on the same datasets. ARIMA and Prophet appeared to be more specialized models better suited for stock prediction data. 

## Interview Readiness

- What is exponential smoothing and why is it used in Time Series Forecasting?

Exponential smoothing methods are a family of forecasting models. They use weighted averages of past observations to forecast new values. It is a method used for univariate data that can be extended to support data with a systematic trend or seasonal component. With exponential smoothing, past observations are weighted with a geometricall decreasing ratio, the weights decay as the observations get older making the more recent observations more impactful.  

- What is stationarity? What is seasonality? Why Is Stationarity Important in Time Series Forecasting?

Stationarity means that the statistical properties of a times series do not change over time. It does not mean that the series does not changed over time, just the way that it changes does not iteself change over time. 
Seasonality is a characteristic of a time series in which the data experiences regular and predictable changes that recur every calendar year. Any predictable fluctuation or pattern that recurs or repeats over a one-year period is said to be seaonsal. 
Stationarity is important in Time Series Forecasting because it because if a Time Series is stationary it means that the statistical properties of the time series are independent of the point in time at which they are observed. There is a constant variance and it always returns to the long-run mean. 

- How is seasonality different from cyclicality? Fill in the blanks:

Seasonality is predictable, whereas cyclicality is not.

