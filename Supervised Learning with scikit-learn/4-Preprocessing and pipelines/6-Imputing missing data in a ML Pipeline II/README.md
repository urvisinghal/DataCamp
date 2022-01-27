Imputing missing data in a ML Pipeline II

Having setup the steps of the pipeline in the previous exercise, you will now use it on the voting dataset to classify a Congressman's party affiliation. What makes pipelines so incredibly useful is the simple interface that they provide. You can use the .fit() and .predict() methods on pipelines just as you did with your classifiers and regressors!

Practice this for yourself now and generate a classification report of your predictions. The steps of the pipeline have been set up for you, and the feature array X and target variable array y have been pre-loaded. Additionally, train_test_split and classification_report have been imported from sklearn.model_selection and sklearn.metrics respectively.

<br>

Instructions

Import the following modules:

Imputer from sklearn.preprocessing and Pipeline from sklearn.pipeline.

SVC from sklearn.svm.

Create the pipeline using Pipeline() and steps.

Create training and test sets. Use 30% of the data for testing and a random state of 42.

Fit the pipeline to the training set and predict the labels of the test set.

Compute the classification report.
