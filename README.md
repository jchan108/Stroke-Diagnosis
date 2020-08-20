# Stroke-Diagnosis

Modeled the association between stroke diagnosis and varying
non-EEG clinical variables through fitting logistic regression
models incorporating spline functions.

Used LASSO regression to address the high dimensional data
induced when also incorporating EEG variables in the model fit.

Determined that the model excluding EEG variables had better
predictive performance in the dataset, through comparing AUC
averaged over 10-fold cross validation
