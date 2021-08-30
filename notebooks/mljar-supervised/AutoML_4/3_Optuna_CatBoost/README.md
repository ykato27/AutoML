# Summary of 3_Optuna_CatBoost

[<< Go back](../README.md)


## CatBoost
- **n_jobs**: -1
- **learning_rate**: 0.2
- **depth**: 4
- **rsm**: 0.6026340876188655
- **loss_function**: RMSE
- **eval_metric**: RMSE
- **l2_leaf_reg**: 1.5395367389239338
- **random_strength**: 0.5355597963917901
- **min_data_in_leaf**: 43
- **num_boost_round**: 1000
- **early_stopping_rounds**: 50
- **explain_level**: 0

## Validation
 - **validation_type**: kfold
 - **k_folds**: 10
 - **shuffle**: True

## Optimized metric
rmse

## Training time

11.6 seconds

### Metric details:
| Metric   |    Score |
|:---------|---------:|
| MAE      | 1.99162  |
| MSE      | 8.77336  |
| RMSE     | 2.96199  |
| R2       | 0.886002 |
| MAPE     | 0.103811 |



## Learning curves
![Learning curves](learning_curves.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



[<< Go back](../README.md)
