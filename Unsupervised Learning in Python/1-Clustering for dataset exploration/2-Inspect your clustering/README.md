Inspect your clustering

Let's now inspect the clustering you performed in the previous exercise!

A solution to the previous exercise has already run, so new_points is an array of points and labels is the array of their cluster labels.

<br>

Instructions

Import matplotlib.pyplot as plt.

Assign column 0 of new_points to xs, and column 1 of new_points to ys.

Make a scatter plot of xs and ys, specifying the c=labels keyword arguments to color the points by their cluster label. Also specify alpha=0.5.

Compute the coordinates of the centroids using the .cluster_centers_ attribute of model.

Assign column 0 of centroids to centroids_x, and column 1 of centroids to centroids_y.

Make a scatter plot of centroids_x and centroids_y, using 'D' (a diamond) as a marker by specifying the marker parameter. Set the size of the markers to be 50 using s=50.
