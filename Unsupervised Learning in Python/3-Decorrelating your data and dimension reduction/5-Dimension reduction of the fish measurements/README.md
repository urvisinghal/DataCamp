Dimension reduction of the fish measurements

In a previous exercise, you saw that 2 was a reasonable choice for the "intrinsic dimension" of the fish measurements. Now use PCA for dimensionality reduction of the fish measurements, retaining only the 2 most important components.

The fish measurements have already been scaled for you, and are available as scaled_samples.

<br>

Instructions

Import PCA from sklearn.decomposition.

Create a PCA instance called pca with n_components=2.

Use the .fit() method of pca to fit it to the scaled fish measurements scaled_samples.

Use the .transform() method of pca to transform the scaled_samples. Assign the result to pca_features.
