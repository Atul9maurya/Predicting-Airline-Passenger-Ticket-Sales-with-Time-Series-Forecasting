# Predicting-Airline-Passenger-Ticket-Sales-with-Time-Series-Forecasting

The goal of this project is to implement and explore various time series forecasting techniques, including **ARIMA, SARIMA, Prophet, and XGBoost**, using a relatively simple and clean dataset.

The dataset utilized in this project is the International Airline Passengers dataset, which records the monthly total number of passengers (in thousands) and includes two columns: month and passenger count.

Key steps in this project include:

- **Data Analysis**: Analyzed the data to check for stationarity and decomposed it into its level, trend, seasonality, and residual components.
- **Stationarity Testing**: Conducted the Augmented Dickey-Fuller (ADF) test to assess stationarity.
- **Model Implementation**: Applied ARIMA, SARIMA, Prophet, and XGBoost models to predict future ticket sales.
- **Performance Evaluation**: Achieved the best accuracy with 19.23% MAPE using the SARIMA model and 14.27% MAPE with the Prophet model.

### Dataset

The dataset used is the International Airline Passengers dataset, which contains the monthly total number of passengers (in thousands) across two columns: month and passenger count.
