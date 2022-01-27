Hyperparameter tuning with GridSearchCV

Hugo demonstrated how to tune the n_neighbors parameter of the KNeighborsClassifier() using GridSearchCV on the voting dataset. You will now practice this yourself, but by using logistic regression on the diabetes dataset instead!

Like the alpha parameter of lasso and ridge regularization that you saw earlier, logistic regression also has a regularization parameter: .  controls the inverse of the regularization strength, and this is what you will tune in this exercise. A large  can lead to an overfit model, while a small  can lead to an underfit model.

The hyperparameter space for  has been setup for you. Your job is to use GridSearchCV and logistic regression to find the optimal  in this hyperparameter space. The feature array is available as X and target variable array is available as y.

You may be wondering why you aren't asked to split the data into training and test sets. Good observation! Here, we want you to focus on the process of setting up the hyperparameter grid and performing grid-search cross-validation. In practice, you will indeed want to hold out a portion of your data for evaluation purposes, and you will learn all about this in the next video!

<br>

Instructions

Import LogisticRegression from sklearn.linear_model and GridSearchCV from sklearn.model_selection.

Setup the hyperparameter grid by using c_space as the grid of values to tune  over.

Instantiate a logistic regression classifier called logreg.

Use GridSearchCV with 5-fold cross-validation to tune :

Inside GridSearchCV(), specify the classifier, parameter grid, and number of folds to use.

Use the .fit() method on the GridSearchCV object to fit it to the data X and y.

Print the best parameter and best score obtained from GridSearchCV by accessing the best_params_ and best_score_ attributes of logreg_cv.
