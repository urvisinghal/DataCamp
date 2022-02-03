Regularized logistic regression

In Chapter 1, you used logistic regression on the handwritten digits data set. Here, we'll explore the effect of L2 regularization.

The handwritten digits dataset is already loaded, split, and stored in the variables X_train, y_train, X_valid, and y_valid. The variables train_errs and valid_errs are already initialized as empty lists.

<br>

Instructions

Loop over the different values of C_value, creating and fitting a LogisticRegression model each time.

Save the error on the training set and the validation set for each model.

Create a plot of the training and testing error as a function of the regularization parameter, C.

Looking at the plot, what's the best value of C?
