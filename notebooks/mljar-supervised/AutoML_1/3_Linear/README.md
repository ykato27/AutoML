# Summary of 3_Linear

[<< Go back](../README.md)


## Linear Regression (Linear)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True

## Optimized metric
rmse

## Training time

7.0 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      |  3.52363  |
| MSE      | 30.9421   |
| RMSE     |  5.56256  |
| R2       |  0.681051 |
| MAPE     |  0.187837 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature   |   Learner_1 |
|:----------|------------:|
| CHAS      |  0.397986   |
| RM        |  0.322976   |
| RAD       |  0.261844   |
| ZN        |  0.130801   |
| B         |  0.109031   |
| AGE       | -0.00327079 |
| intercept | -0.0275832  |
| INDUS     | -0.050367   |
| NOX       | -0.14498    |
| PTRATIO   | -0.150847   |
| CRIM      | -0.164443   |
| TAX       | -0.211143   |
| DIS       | -0.329154   |
| LSTAT     | -0.405136   |


## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions (Fold 1)
![SHAP worst decisions from fold 1](learner_fold_0_shap_worst_decisions.png)
### Top-10 Best decisions (Fold 1)
![SHAP best decisions from fold 1](learner_fold_0_shap_best_decisions.png)

[<< Go back](../README.md)
