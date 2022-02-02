Regularization I: Lasso

In the video, you saw how Lasso selected out the 'RM' feature as being the most important for predicting Boston house prices, while shrinking the coefficients of certain other features to 0. Its ability to perform feature selection in this way becomes even more useful when you are dealing with data involving thousands of features.

In this exercise, you will fit a lasso regression to the Gapminder data you have been working with and plot the coefficients. Just as with the Boston data, you will find that the coefficients of some features are shrunk to 0, with only the most important ones remaining.

The feature and target variable arrays have been pre-loaded as X and y.

<br>

Instructions

Import Lasso from sklearn.linear_model.

Instantiate a Lasso regressor with an alpha of 0.4 and specify normalize=True.

Fit the regressor to the data and compute the coefficients using the coef_ attribute.

Plot the coefficients on the y-axis and column names on the x-axis. This has been done for you, so hit submit to view the plot!
