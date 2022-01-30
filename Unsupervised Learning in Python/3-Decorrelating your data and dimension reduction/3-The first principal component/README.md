The first principal component

The first principal component of the data is the direction in which the data varies the most. In this exercise, your job is to use PCA to find the first principal component of the length and width measurements of the grain samples, and represent it as an arrow on the scatter plot.

The array grains gives the length and width of the grain samples. PyPlot (plt) and PCA have already been imported for you.

<br>

Instructions

Make a scatter plot of the grain measurements. This has been done for you.

Create a PCA instance called model.

Fit the model to the grains data.

Extract the coordinates of the mean of the data using the .mean_ attribute of model.

Get the first principal component of model using the .components_[0,:] attribute.

Plot the first principal component as an arrow on the scatter plot, using the plt.arrow() function. You have to specify the first two arguments - mean[0] and mean[1].
