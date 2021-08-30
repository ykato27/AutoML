# Summary of 2_Optuna_Xgboost_Stacked

[<< Go back](../README.md)


## Extreme Gradient Boosting (Xgboost)
- **n_jobs**: -1
- **objective**: reg:squarederror
- **eta**: 0.0125
- **max_depth**: 8
- **min_child_weight**: 2
- **subsample**: 0.47732203253202954
- **colsample_bytree**: 0.9439467767716354
- **eval_metric**: rmse
- **lambda**: 0.00789742283515979
- **alpha**: 3.266185187119584e-06
- **max_rounds**: 1000
- **early_stopping_rounds**: 50
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **k_folds**: 10
 - **shuffle**: True

## Optimized metric
rmse

## Training time

43.9 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      |  2.1448   |
| MSE      | 10.1594   |
| RMSE     |  3.18738  |
| R2       |  0.867993 |
| MAPE     |  0.118818 |



## Learning curves
![Learning curves](learning_curves.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



[<< Go back](../README.md)
