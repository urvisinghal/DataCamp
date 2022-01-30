Hierarchical clustering of the grain data

In the video, you learned that the SciPy linkage() function performs hierarchical clustering on an array of samples. Use the linkage() function to obtain a hierarchical clustering of the grain samples, and use dendrogram() to visualize the result. A sample of the grain measurements is provided in the array samples, while the variety of each grain sample is given by the list varieties.

<br>

Instructions

Import:  
linkage and dendrogram from scipy.cluster.hierarchy.  
matplotlib.pyplot as plt.  

Perform hierarchical clustering on samples using the linkage() function with the method='complete' keyword argument. Assign the result to mergings.

Plot a dendrogram using the dendrogram() function on mergings. Specify the keyword arguments labels=varieties, leaf_rotation=90, and leaf_font_size=6.
