# algal-growth-time-series-analysis
Time series analysis and forecasting of algal growth using Excel

# Algal Growth Time Series Analysis (Excel)

## Problem
Analyze algal growth (g/L) measured in the Gulf of Mexico using sensor-based resistance measurements. The goal is to identify trends, seasonality, and build a governing equation for forecasting.

## Tools
- Microsoft Excel
- Time Series Analysis
- Moving Averages
- Exponential Smoothing
- Error Metrics (MAD, MSE, RMSE, MAPE)

## Methodology
1. Exploratory Data Analysis to detect trend and seasonality
2. Linear trend modeling
3. Smoothing using:
   - Moving Average (3, 4, 6 periods)
   - Exponential Smoothing (α = 0.1, 0.2)
4. Model comparison using error metrics
5. Governing equation combining trend + seasonal components
6. Residual analysis to validate model assumptions

## Governing Equation
y = 0.00075x + 5.509 + A·sin(x/p + s) + A·cos(x/p + s) + d

## Results
- Clear seasonal behavior with increasing long-term trend
- Exponential smoothing (α = 0.1) performed best
- Residuals randomly distributed around zero
- Model suitable for short- and long-term forecasting

## Key Skills Demonstrated
- Time series decomposition
- Forecasting
- Model evaluation
- Analytical reasoning
- Business interpretation

## Author
Smit Patel
