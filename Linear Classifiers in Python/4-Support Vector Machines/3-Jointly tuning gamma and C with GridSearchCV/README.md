Jointly tuning gamma and C with GridSearchCV

In the previous exercise the best value of gamma was 0.001 using the default value of C, which is 1. In this exercise you'll search for the best combination of C and gamma using GridSearchCV.

As in the previous exercise, the 2-vs-not-2 digits dataset is already loaded, but this time it's split into the variables X_train, y_train, X_test, and y_test. Even though cross-validation already splits the training set into parts, it's often a good idea to hold out a separate test set to make sure the cross-validation results are sensible.

<br>

Instructions

Run GridSearchCV to find the best hyperparameters using the training set.

Print the best values of the parameters.

Print out the accuracy on the test set, which was not used during the cross-validation procedure.
