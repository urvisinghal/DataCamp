A t-SNE map of the stock market

t-SNE provides great visualizations when the individual samples can be labeled. In this exercise, you'll apply t-SNE to the company stock price data. A scatter plot of the resulting t-SNE features, labeled by the company names, gives you a map of the stock market! The stock price movements for each company are available as the array normalized_movements (these have already been normalized for you). The list companies gives the name of each company. PyPlot (plt) has been imported for you.

<br>

Instructions

Import TSNE from sklearn.manifold.

Create a TSNE instance called model with learning_rate=50.

Apply the .fit_transform() method of model to normalized_movements. Assign the result to tsne_features.

Select column 0 and column 1 of tsne_features.

Make a scatter plot of the t-SNE features xs and ys. Specify the additional keyword argument alpha=0.5.

Code to label each point with its company name has been written for you using plt.annotate(), so just hit submit to see the visualization!
