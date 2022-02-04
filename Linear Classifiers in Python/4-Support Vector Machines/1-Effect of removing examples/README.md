Effect of removing examples

Support vectors are defined as training examples that influence the decision boundary. In this exercise, you'll observe this behavior by removing non support vectors from the training set.

The wine quality dataset is already loaded into X and y (first two features only). (Note: we specify lims in plot_classifier() so that the two plots are forced to use the same axis limits and can be compared directly.)

<br>

Instructions

Train a linear SVM on the whole data set.

Create a new data set containing only the support vectors.

Train a new linear SVM on the smaller data set.
