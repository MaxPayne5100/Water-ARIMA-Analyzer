# Water-ARIMA-Analyzer
Project to forecast water pollution using ARIMA method

## ETL Function for Time Series Analysis and Forecasting
This project implements a comprehensive Extract, Transform, Load (ETL) function developed within the Google Colaboratory environment. It is designed to automate the end-to-end process of time series data analysis, forecasting, and result management, with seamless integration with Google Drive for data ingestion and output storage.

## Key Features
* Data Extraction (E):

  Securely loads raw CSV data directly from Google Drive.
  Utilizes a dynamic configuration file (also loaded from Google Drive) to define processing parameters.
* Data Transformation & Analysis (T):

  Performs data processing and cleaning based on specified parameters from the configuration file.
  Conducts in-depth time series analysis, including:
  Decomposition: Separation of observed data into trend, seasonal, and residual components.
  Statistical Analysis: Generation of descriptive statistics.
  Autocorrelation and Partial Autocorrelation Functions (ACF/PACF): For understanding data dependencies and informing model order selection.

* Model Building & Forecasting (M):

  Implements ARIMA (AutoRegressive Integrated Moving Average) modeling for time series forecasting.
  Features user-guided parameter detection utilizing first-order-differenced ACF/PACF plots for optimal model selection.
* Validation & Evaluation:

  Estimates various error metrics (e.g., MAE, MSE, RMSE) to assess model performance.
  Incorporates cross-validation techniques for robust model evaluation.
* Dashboard Creation:

  Generates informative data visualization dashboards, including decomposition plots, histograms, and ACF/PACF plots, for quick insights into the data and model behavior.
* Load (L):

  All generated results, including processed data, model outputs, and visual dashboards, are systematically uploaded back to Google Drive for persistent storage and easy access.

## Environment
This solution is engineered to operate efficiently within a Google Colaboratory runtime, leveraging its seamless integration with Google Drive and powerful computing resources.