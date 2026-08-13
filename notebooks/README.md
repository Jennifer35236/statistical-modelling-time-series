# Analysis Notebook

This directory contains the Jupyter Notebook developed for the **Statistics and Optimization** project.

## Project Components

The notebook covers two main areas of statistical analysis.

### Multiple Linear Regression

The regression workflow includes:

- exploratory data analysis
- descriptive statistics
- categorical variable encoding
- outlier detection
- train/test splitting
- multiple linear regression modelling
- coefficient interpretation
- Variance Inflation Factor (VIF) analysis
- residual diagnostics
- model evaluation

The final reported regression model achieved:

| Metric | Result |
|---|---:|
| R² | 0.638 |
| Mean Squared Error | 1,532,916 |

### Time Series Analysis

The time-series component explores:

- time-series visualisation
- stationarity analysis
- Augmented Dickey-Fuller testing
- log transformation
- differencing
- ARIMA modelling
- Holt-Winters Exponential Smoothing
- forecast evaluation
- residual analysis

The original forecasting evaluation reported:

| Metric | Result |
|---|---:|
| MSE | 258.90 |
| MAE | 13.71 |

## Reproducibility Note

The original Multiple Linear Regression dataset is available in the repository under `data/mlr1.csv`.

The original source dataset used for the time-series component is no longer available. The notebook and original project documentation are retained to preserve the methodology and results, but the time-series section cannot be fully reproduced without that source dataset.
