Which articles are similar to 'Cristiano Ronaldo'?

In the video, you learned how to use NMF features and the cosine similarity to find similar articles. Apply this to your NMF model for popular Wikipedia articles, by finding the articles most similar to the article about the footballer Cristiano Ronaldo. The NMF features you obtained earlier are available as nmf_features, while titles is a list of the article titles.

<br>

Instructions

Import normalize from sklearn.preprocessing.

Apply the normalize() function to nmf_features. Store the result as norm_features.

Create a DataFrame df from norm_features, using titles as an index.

Use the .loc[] accessor of df to select the row of 'Cristiano Ronaldo'. Assign the result to article.

Apply the .dot() method of df to article to calculate the cosine similarity of every row with article.

Print the result of the .nlargest() method of similarities to display the most similiar articles. This has been done for you, so hit submit to see the result!
