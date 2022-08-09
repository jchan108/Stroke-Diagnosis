# Stroke-Diagnosis

This project was meant to look into the issue of being able to diagnosis whether or not a patient has had a stroke before they make it to the hospital.

Modeled the association between stroke diagnosis and varying
non-EEG clinical variables through fitting logistic regression
models incorporating spline functions.

Used LASSO regression to address the high dimensional data
induced when also incorporating EEG variables in the model fit.

Determined that the model excluding EEG variables had better
predictive performance in the dataset, through comparing AUC
averaged over 10-fold cross validation
