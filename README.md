# Airline_Flight_Demand_Forecasting

This project performs time series analysis and forecasting on monthly air passenger traffic data to predict future air ticket demand.

### 1. Data
The dataset contains 144 observations of monthly total airline passengers from 1949 to 1960. It can be found in the AirPassengers.csv file.

### 2. Methods
The following analyses and models are implemented:

* Visualization - Time series plots, distribution analysis
* Preprocessing - Date parsing, indexing, train-test split
* Decomposition - Trend, seasonality, noise analysis
* Stationarity - Rolling statistics, Dickey-Fuller test
* Transformations - Differencing, Box-Cox to make series stationary
* Modeling - Auto ARIMA, SARIMAX
* Forecasting on test set
* Model evaluation - AIC, train-test plots
* Key Python libraries used: Pandas, Statsmodels, Matplotlib, Scikit-learn

### 3. Results

* The time series showed increasing trend and seasonality patterns
* Differencing and Box-Cox transformation made the series stationary
* SARIMAX model with orders (1,1,1)(1,1,1,12) performed best with lowest AIC
* The model achieved a low MAPE of 3.5% on the test set
* Forecasts followed the seasonal patterns seen in the historical data

Overall, the analysis showed that time series techniques can effectively model and forecast seasonal ticket demand patterns. The SARIMAX model successfully captured the trends and seasonality.
