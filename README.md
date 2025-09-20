# InternIntelligence_Time_Series_Forecasting
Time Series Forecasting

This project demonstrates time series forecasting using a dataset of product sales (ProductP1–ProductP5), along with related features like price and temperature. The goal is to build forecasting models, evaluate their performance, and visualize predictions against actual values.

**Project Workflow:
1. Data Collection & Exploration

Loaded dataset with 100 time-indexed entries.

Columns include: t, ProductP1 … ProductP5, price, temperature.

Verified no missing values and performed descriptive statistics.

2. Model Development

Implemented three forecasting models on ProductP1:

ARIMA (AutoRegressive Integrated Moving Average)

SARIMA (Seasonal ARIMA)

Prophet (Facebook’s forecasting model)

3. Evaluation

Models were evaluated using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

Example ARIMA results:

MAE: 13.61

RMSE: 16.17

4. Visualization

Forecasted values were plotted against actual test values for easy comparison.

**Results:

ARIMA performed best among the tested models.

SARIMA and Prophet gave higher errors but still captured the trend.

Visualization clearly shows the alignment between forecast and actual sales values.

**Tech Stack:

Python

Pandas, NumPy

Statsmodels (ARIMA, SARIMA)

Prophet

Matplotlib

scikit-learn (Evaluation Metrics)

**Future Improvements:

Extend forecasting to multiple product series (ProductP2 … ProductP5).

Hyperparameter tuning for ARIMA/SARIMA.

Incorporate external regressors (price, temperature).

Deploy as a web app for interactive forecasting.
