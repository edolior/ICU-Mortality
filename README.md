The challenge is to create a prediction model that uses data from the first 24 hours of intensive care units (ICUs) to predict patient survival. MIT's GOSSIS community initiative, with privacy certification from the Harvard Privacy Lab, has provided a dataset of more than 130,000 hospital ICU visits from patients.

Preprocessing: hold-out validation, one-hot encoding categorical features, multiple-imputation
Classifiers: LR, RF & GAM
Evaluations Metrices: AUC, PR-AUC
Explainability Global: Lasso, Random Forest Regressor, Global Surrogate Model Decision Tree Regressor, SHAP Summary, PDP.
Explainability Local: LIME, SHAP Force.
Fairness: Multi-Calibration post processing calibration correction algorithm.
