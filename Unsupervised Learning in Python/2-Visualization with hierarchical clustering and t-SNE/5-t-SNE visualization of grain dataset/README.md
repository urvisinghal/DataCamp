t-SNE visualization of grain dataset

In the video, you saw t-SNE applied to the iris dataset. In this exercise, you'll apply t-SNE to the grain samples data and inspect the resulting t-SNE features using a scatter plot. You are given an array samples of grain samples and a list variety_numbers giving the variety number of each grain sample.

<br>

Instructions

Import TSNE from sklearn.manifold.

Create a TSNE instance called model with learning_rate=200.

Apply the .fit_transform() method of model to samples. Assign the result to tsne_features.

Select the column 0 of tsne_features. Assign the result to xs.

Select the column 1 of tsne_features. Assign the result to ys.

Make a scatter plot of the t-SNE features xs and ys. To color the points by the grain variety, specify the additional keyword argument c=variety_numbers.
