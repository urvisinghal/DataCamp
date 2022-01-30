Variance of the PCA features

The fish dataset is 6-dimensional. But what is its intrinsic dimension? Make a plot of the variances of the PCA features to find out. As before, samples is a 2D array, where each row represents a fish. You'll need to standardize the features first.

<br>

Instructions

Create an instance of StandardScaler called scaler.

Create a PCA instance called pca.

Use the make_pipeline() function to create a pipeline chaining scaler and pca.

Use the .fit() method of pipeline to fit it to the fish samples samples.

Extract the number of components used using the .n_components_ attribute of pca. Place this inside a range() function and store the result as features.

Use the plt.bar() function to plot the explained variances, with features on the x-axis and pca.explained_variance_ on the y-axis.
