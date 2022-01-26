5-fold cross-validation

Cross-validation is a vital step in evaluating a model. It maximizes the amount of data that is used to train the model, as during the course of training, the model is not only trained, but also tested on all of the available data.

In this exercise, you will practice 5-fold cross validation on the Gapminder data. By default, scikit-learn's cross_val_score() function uses  as the metric of choice for regression. Since you are performing 5-fold cross-validation, the function will return 5 scores. Your job is to compute these 5 scores and then take their average.

The DataFrame has been loaded as df and split into the feature/target variable arrays X and y. The modules pandas and numpy have been imported as pd and np, respectively.

<br>

Instructions

Import LinearRegression from sklearn.linear_model and cross_val_score from sklearn.model_selection.

Create a linear regression regressor called reg.

Use the cross_val_score() function to perform 5-fold cross-validation on X and y.

Compute and print the average cross-validation score. You can use NumPy's mean() function to compute the average.
