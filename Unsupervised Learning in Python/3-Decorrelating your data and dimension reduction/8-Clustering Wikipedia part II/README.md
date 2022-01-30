Clustering Wikipedia part II

It is now time to put your pipeline from the previous exercise to work! You are given an array articles of tf-idf word-frequencies of some popular Wikipedia articles, and a list titles of their titles. Use your pipeline to cluster the Wikipedia articles.

A solution to the previous exercise has been pre-loaded for you, so a Pipeline pipeline chaining TruncatedSVD with KMeans is available.

<br>

Instructions

Import pandas as pd.

Fit the pipeline to the word-frequency array articles.

Predict the cluster labels.

Align the cluster labels with the list titles of article titles by creating a DataFrame df with labels and titles as columns. This has been done for you.

Use the .sort_values() method of df to sort the DataFrame by the 'label' column, and print the result.

Hit submit and take a moment to investigate your amazing clustering of Wikipedia pages!
