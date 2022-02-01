NMF applied to Wikipedia articles

In the video, you saw NMF applied to transform a toy word-frequency array. Now it's your turn to apply NMF, this time using the tf-idf word-frequency array of Wikipedia articles, given as a csr matrix articles. Here, fit the model and transform the articles. In the next exercise, you'll explore the result.

<br>

Instructions

Import NMF from sklearn.decomposition.

Create an NMF instance called model with 6 components.

Fit the model to the word count data articles.

Use the .transform() method of model to transform articles, and assign the result to nmf_features.

Print nmf_features to get a first idea what it looks like (.round(2) rounds the entries to 2 decimal places.)
