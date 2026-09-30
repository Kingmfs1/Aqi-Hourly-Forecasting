# AQI Hourly Forecasting — Isfahan

Hourly forecasting of the Air Quality Index (AQI) for Isfahan, Iran, using a Stacking ensemble of machine learning models.

## Overview

This project builds a nowcasting model to predict the next-hour AQI using historical air quality data (2018–2025, hourly frequency, ~70,000 samples). The model combines LightGBM and XGBoost as base learners with a Ridge regression meta-learner.

## Results

| Metric              | Value    |
|---------------------|----------|
| Test RMSE           | 4.19     |
| Test R²             | 0.9845   |
| Baseline RMSE       | 4.94     |
| Improvement vs Base | 15.2%    |


