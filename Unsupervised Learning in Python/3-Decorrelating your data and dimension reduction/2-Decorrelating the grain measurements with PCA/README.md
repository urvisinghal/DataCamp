Decorrelating the grain measurements with PCA

You observed in the previous exercise that the width and length measurements of the grain are correlated. Now, you'll use PCA to decorrelate these measurements, then plot the decorrelated points and measure their Pearson correlation.

<br>

Instructions

Import PCA from sklearn.decomposition.

Create an instance of PCA called model.

Use the .fit_transform() method of model to apply the PCA transformation to grains. Assign the result to pca_features.

The subsequent code to extract, plot, and compute the Pearson correlation of the first two columns pca_features has been written for you, so hit submit to see the result!
