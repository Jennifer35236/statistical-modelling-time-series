# Project Visuals

This directory contains original visualisations from the **Statistical Modelling & Time Series Forecasting** project.

The figures cover both components of the analysis:

1. Multiple Linear Regression
2. Time Series Analysis and Forecasting

---

## Multiple Linear Regression Visualisations

### Correlation Heatmap

`correlation-heatmap.png`

The correlation heatmap was used during exploratory data analysis to examine relationships between the predictors and the target variable.

It helped identify the strength and direction of relationships between variables and supported the assessment of their predictive potential.

### Residual Distribution

`residual-distribution.png`

The residual distribution was examined as part of the regression diagnostic process.

The approximately bell-shaped distribution centred around zero supports the assumption that the regression residuals are approximately normally distributed.

### Residuals vs Fitted Values

`residuals-vs-fitted.png`

This diagnostic plot compares regression residuals with fitted values.

The residuals are distributed around zero without a strong systematic pattern, supporting the assessment of homoscedasticity and the suitability of the linear regression model.

### Q-Q Plot of Residuals

`qq-plot-residuals.png`

The Q-Q plot compares the observed residual quantiles with theoretical normal-distribution quantiles.

Most observations follow the reference line reasonably closely, providing additional evidence that the residuals are approximately normally distributed.

---

## Time Series Visualisations

### Log-Transformed Time Series

`log-transformed-time-series.png`

A logarithmic transformation was applied to the original time series to stabilise variance and make the underlying temporal behaviour easier to analyse.

This formed part of the preparation process before fitting forecasting models.

### Differenced Time Series

`differenced-time-series.png`

Differencing was applied to reduce trend and improve stationarity.

The transformed series was used to prepare the data for statistical time-series modelling.

### Actual vs Forecast Values

`actual-vs-forecast-sarima.png`

This visual compares actual test observations with forecasted values from the time-series modelling process.

It provides a direct visual assessment of how closely the forecasting model follows the behaviour of the unseen test data.

---

## Purpose

Together, these figures demonstrate the project's statistical workflow from exploratory analysis through model diagnostics and time-series forecasting.

They provide visual evidence of:

- predictor relationships
- regression residual behaviour
- homoscedasticity assessment
- residual normality
- time-series transformation
- stationarity preparation
- forecast evaluation

The original time-series source dataset is no longer available in the repository. These original project figures have therefore been retained to document the analysis without attempting to recreate or fabricate the missing source data.
