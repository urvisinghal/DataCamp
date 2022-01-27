Bringing it all together I: Pipeline for classification

It is time now to piece together everything you have learned so far into a pipeline for classification! Your job in this exercise is to build a pipeline that includes scaling and hyperparameter tuning to classify wine quality.

You'll return to using the SVM classifier you were briefly introduced to earlier in this chapter. The hyperparameters you will tune are  and .  controls the regularization strength. It is analogous to the  you tuned for logistic regression in Chapter 3, while  controls the kernel coefficient: Do not worry about this now as it is beyond the scope of this course.

The following modules and functions have been pre-loaded: Pipeline, SVC, train_test_split, GridSearchCV, classification_report, accuracy_score. The feature and target variable arrays X and y have also been pre-loaded.

<br>

Instructions

Setup the pipeline with the following steps:

Scaling, called 'scaler' with StandardScaler().

Classification, called 'SVM' with SVC().

Specify the hyperparameter space using the following notation: 'step_name__parameter_name'. Here, the step_name is SVM, and the parameter_names are C and gamma.

Create training and test sets, with 20% of the data used for the test set. Use a random state of 21.

Instantiate GridSearchCV with the pipeline and hyperparameter space and fit it to the training set. Use 3-fold cross-validation (This is the default, so you don't have to specify it).

Predict the labels of the test set and compute the metrics. The metrics have been computed for you.
