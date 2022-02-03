Logistic regression and feature selection

In this exercise we'll perform feature selection on the movie review sentiment data set using L1 regularization. The features and targets are already loaded for you in X_train and y_train.

We'll search for the best value of C using scikit-learn's GridSearchCV(), which was covered in the prerequisite course.

<br>

Instructions

Instantiate a logistic regression object that uses L1 regularization.

Find the value of C that minimizes cross-validation error.

Print out the number of selected features for this value of C.
