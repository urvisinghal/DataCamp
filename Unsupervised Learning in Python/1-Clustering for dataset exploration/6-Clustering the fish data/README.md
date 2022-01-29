Clustering the fish data

You'll now use your standardization and clustering pipeline from the previous exercise to cluster the fish by their measurements, and then create a cross-tabulation to compare the cluster labels with the fish species.

As before, samples is the 2D array of fish measurements. Your pipeline is available as pipeline, and the species of every fish sample is given by the list species.

<br>

Instructions

Import pandas as pd.

Fit the pipeline to the fish measurements samples.

Obtain the cluster labels for samples by using the .predict() method of pipeline.

Using pd.DataFrame(), create a DataFrame df with two columns named 'labels' and 'species', using labels and species, respectively, for the column values.

Using pd.crosstab(), create a cross-tabulation ct of df['labels'] and df['species'].
