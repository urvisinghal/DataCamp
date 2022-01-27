Hyperparameter tuning with RandomizedSearchCV

GridSearchCV can be computationally expensive, especially if you are searching over a large hyperparameter space and dealing with multiple hyperparameters. A solution to this is to use RandomizedSearchCV, in which not all hyperparameter values are tried out. Instead, a fixed number of hyperparameter settings is sampled from specified probability distributions. You'll practice using RandomizedSearchCV in this exercise and see how this works.

Here, you'll also be introduced to a new model: the Decision Tree. Don't worry about the specifics of how this model works. Just like k-NN, linear regression, and logistic regression, decision trees in scikit-learn have .fit() and .predict() methods that you can use in exactly the same way as before. Decision trees have many parameters that can be tuned, such as max_features, max_depth, and min_samples_leaf: This makes it an ideal use case for RandomizedSearchCV.

As before, the feature array X and target variable array y of the diabetes dataset have been pre-loaded. The hyperparameter settings have been specified for you. Your goal is to use RandomizedSearchCV to find the optimal hyperparameters. Go for it!

<br>

Instructions

Import DecisionTreeClassifier from sklearn.tree and RandomizedSearchCV from sklearn.model_selection.

Specify the parameters and distributions to sample from. This has been done for you.

Instantiate a DecisionTreeClassifier.

Use RandomizedSearchCV with 5-fold cross-validation to tune the hyperparameters:

Inside RandomizedSearchCV(), specify the classifier, parameter distribution, and number of folds to use.

Use the .fit() method on the RandomizedSearchCV object to fit it to the data X and y.

Print the best parameter and best score obtained from RandomizedSearchCV by accessing the best_params_ and best_score_ attributes of tree_cv.
