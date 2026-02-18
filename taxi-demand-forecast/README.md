# Taxi Demand Forecasting — Time Series Prediction

Time series forecasting project aimed at predicting hourly taxi demand using historical airport request data.

## Objective

Develop predictive models capable of forecasting taxi demand one hour ahead to support operational planning and driver allocation during peak periods.

## Dataset

Historical taxi order data containing:

- Timestamp (datetime)
- Number of taxi orders

Original data recorded at sub-hourly frequency and aggregated to hourly demand.

## Methodology

### Data Preparation
- Datetime validation and conversion
- Removal of invalid timestamps
- Sorting and indexing time series
- Hourly resampling of demand data
- Missing value handling

### Exploratory Analysis
- Statistical distribution analysis
- Autocorrelation inspection
- Temporal behavior evaluation

### Modeling
- Linear Regression
- Random Forest Regressor
- Hyperparameter experimentation

### Evaluation

Performance evaluated using RMSE with project constraint:

RMSE ≤ 48 on test dataset.

## Results

Models successfully captured temporal demand dynamics and satisfied performance requirements for operational forecasting.

## Technologies

- Python
- Pandas
- Scikit-learn
- Time Series Processing
- Data Visualization

## Skills Demonstrated

- Time series forecasting
- Temporal feature engineering
- Demand prediction
- Model evaluation
- Business-oriented analytics

## Author

Víctor Chang Baca
