# Stock-Price-Prediction-Comparison-of-ARIMA-and-LSTM
Stock Price Prediction for NVIDIA and AMD (2018 Q4-2023 Q3) using ARIMA and LSTM models. This project explores market trends, compares model performances, and introduces a Hybrid ARIMA-LSTM approach for improved forecasting accuracy.

This project delves into predictive analysis of stock prices for NVIDIA Corporation (NVDA) and Advanced Micro Devices, Inc. (AMD) from Q4 2018 to Q3 2023. We explore auto-regressive structures, assess market dynamics, and forecast future prices using ARIMA and LSTM models, along with a novel Hybrid ARIMA-LSTM approach for enhanced accuracy.

# Data Description
We examine the stocks of NVDA and AMD during a period marked by significant technological and economic changes, including AI advancements and cryptocurrency trends. The data encompasses daily closing prices, providing a rich landscape for our predictive analysis.

# Data Preprocessing
Checked for missing values.
Decomposed time series data to analyze trend, seasonality, and residuals.
Conducted Augmented Dickey-Fuller (ADF) tests to ensure stationarity.
Applied transformations (log and first difference) to achieve stationarity.
# Methodology
ARIMA Model: Applied for its effectiveness in linear time series forecasting. Parameters (p, d, q) were optimized based on AIC and BIC values.
LSTM Model: Used to capture non-linear relationships in data. Look-back window was optimized to minimize RMSE.
Hybrid ARIMA-LSTM Model: Developed to combine linear and non-linear predictive capabilities, achieving a significantly low testing RMSE.

# Analysis and Results
ARIMA models provided better prediction accuracy for both stocks compared to LSTM models.
The simpler ARIMA model was more effective despite the LSTM’s ability to capture complex patterns.
The Hybrid model set a new benchmark in forecasting accuracy.

# Model Comparison
Comparative analysis of ARIMA and LSTM models is provided, with emphasis on RMSE as the performance metric.
Insights into model suitability and limitations are discussed.

# Conclusion
The analysis highlights the effectiveness of ARIMA in stock price prediction for AMD and NVDA. While LSTM models offer advanced capabilities, their complexity does not always guarantee superior performance. This study provides a comprehensive view of the strengths and weaknesses of both models in financial forecasting.

# References
Time Series Analysis by James D. Hamilton
