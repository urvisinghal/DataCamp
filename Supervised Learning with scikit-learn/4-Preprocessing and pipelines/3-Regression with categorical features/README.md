Regression with categorical features

Having created the dummy variables from the 'Region' feature, you can build regression models as you did before. Here, you'll use ridge regression to perform 5-fold cross-validation.

The feature array X and target variable array y have been pre-loaded.

<br>

Instructions

Import Ridge from sklearn.linear_model and cross_val_score from sklearn.model_selection.

Instantiate a ridge regressor called ridge with alpha=0.5 and normalize=True.

Perform 5-fold cross-validation on X and y using the cross_val_score() function.

Print the cross-validated scores.
