# Gold Recovery Prediction — Industrial Machine Learning Model

Machine learning project focused on predicting gold recovery in a metallurgical process using operational variables available before process completion.

## Objective

Develop a predictive model capable of estimating gold recovery while preventing data leakage and ensuring realistic industrial deployment conditions.

## Dataset

Industrial metallurgical process data including multiple stages:

- Rougher stage
- Primary cleaning
- Final recovery

Observations include chemical concentrations, process inputs, and operational measurements.

## Methodology

### Data Preparation
- Validation of recovery calculation integrity (MAE ≈ 10⁻¹⁴)
- Removal of physically implausible observations
- Detection and exclusion of unavailable test variables
- Prevention of data leakage

### Exploratory Data Analysis
- Metal concentration behavior across stages
- Distribution comparison between train and test datasets
- Outlier identification

### Modeling
- Ridge Regression (multi-output)
- Pipeline with:
  - Median imputation
  - Feature scaling
- TimeSeriesSplit cross-validation

### Evaluation Metric
- sMAPE (weighted):
  - Final recovery: 75%
  - Rougher recovery: 25%

## Results

- Cross-validation sMAPE: 10.80
- Test sMAPE: 9.25
- Strong generalization performance without overfitting.

## Technologies

- Python
- Pandas
- Scikit-learn
- Machine Learning Pipelines
- Time Series Validati
