Centering and scaling in a pipeline

With regard to whether or not scaling is effective, the proof is in the pudding! See for yourself whether or not scaling the features of the White Wine Quality dataset has any impact on its performance. You will use a k-NN classifier as part of a pipeline that includes scaling, and for the purposes of comparison, a k-NN classifier trained on the unscaled data has been provided.

The feature array and target variable array have been pre-loaded as X and y. Additionally, KNeighborsClassifier and train_test_split have been imported from sklearn.neighbors and sklearn.model_selection, respectively.

<br>

Instructions

Import the following modules:

StandardScaler from sklearn.preprocessing.

Pipeline from sklearn.pipeline.

Complete the steps of the pipeline with StandardScaler() for 'scaler' and KNeighborsClassifier() for 'knn'.

Create the pipeline using Pipeline() and steps.

Create training and test sets, with 30% used for testing. Use a random state of 42.

Fit the pipeline to the training set.

Compute the accuracy scores of the scaled and unscaled models by using the .score() method inside the provided print() functions.
