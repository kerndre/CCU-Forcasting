# Forecasting Concurrent User for Online Radio Stream

## Repository Link

https://github.com/kerndre/CCU-Forcasting/

## Description

This project deals with the task of predicting the number of concurrent users of an online stream of a radio streaming service. For this purpose, the models XGBoost Regressor and LightGBM Regressor are used.

### Task Type

Predicting/Forecasting

### Results Summary

- **Best Model:** XGBoost_optimized {'learning_rate': 0.25, 'max_depth': 5, 'n_estimators': 25, 'seed':42} # rest of hyperparameter are default
- **Evaluation Metric:** MSE, MAE, R2, Explained Variance
- **Result:**
  - **MSE**: 2622.032948
  - **MAE**: 34.342699
  - **R²**: 0.978864
  - **Explained Variance**: 0.978941 

## Documentation

1. **[Dataset Characteristics](https://github.com/kerndre/CCU-Forcasting/blob/3be878163b94d6f798917e49e019ca18372e4a26/1_DatasetCharacteristics/dataset_advanced_time_series_analysis_optimized.ipynb)**
2. **[Baseline Model](https://github.com/kerndre/CCU-Forcasting/blob/abcb395636736170893e756366261a4a7edd102f/2_BaselineModel/baseline_advanced_time_series_analysis.ipynb)**
3. **[Model Definition and Evaluation](https://github.com/kerndre/CCU-Forcasting/blob/0abd273e6b38a42351b33949d25aaf0dacfde3ce/3_Model/model_advanced_time_series_analysis.ipynb)**
4. **[Presentation](https://github.com/kerndre/CCU-Forcasting/blob/9ecd29bbfdbc10d68c8131b78fc4d71b4279d490/4_Presentation/Presentation%20-%20Project%20Advanced%20Time%20Series%20Analysis.pdf)**
