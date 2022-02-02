Hold-out set in practice II: Regression

Remember lasso and ridge regression from the previous chapter? Lasso used the  penalty to regularize, while ridge used the  penalty. There is another type of regularized regression known as the elastic net. In elastic net regularization, the penalty term is a linear combination of the  and  penalties:


In scikit-learn, this term is represented by the 'l1_ratio' parameter: An 'l1_ratio' of 1 corresponds to an  penalty, and anything lower is a combination of  and .

In this exercise, you will GridSearchCV to tune the 'l1_ratio' of an elastic net model trained on the Gapminder data. As in the previous exercise, use a hold-out set to evaluate your model's performance.

<br>

Instructions

Import the following modules:  
``ElasticNet from sklearn.linear_model.  
mean_squared_error from sklearn.metrics.  
GridSearchCV and train_test_split from sklearn.model_selection.``

Create training and test sets, with 40% of the data used for the test set. Use a random state of 42.

Specify the hyperparameter grid for 'l1_ratio' using l1_space as the grid of values to search over.

Instantiate the ElasticNet regressor.

Use GridSearchCV with 5-fold cross-validation to tune 'l1_ratio' on the training data X_train and y_train. This involves first instantiating the GridSearchCV object with the correct parameters and then fitting it to the training data.

Predict on the test set and compute the  and mean squared error.
