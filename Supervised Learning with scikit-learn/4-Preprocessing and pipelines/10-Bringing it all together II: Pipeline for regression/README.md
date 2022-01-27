
Bringing it all together II: Pipeline for regression
For this final exercise, you will return to the Gapminder dataset. Guess what? Even this dataset has missing values that we dealt with for you in earlier chapters! Now, you have all the tools to take care of them yourself!

Your job is to build a pipeline that imputes the missing data, scales the features, and fits an ElasticNet to the Gapminder data. You will then tune the l1_ratio of your ElasticNet using GridSearchCV.

All the necessary modules have been imported, and the feature and target variable arrays have been pre-loaded as X and y.

<br>

Instructions

Set up a pipeline with the following steps:  
'imputation', which uses the Imputer() transformer and the 'mean' strategy to impute missing data ('NaN') using the mean of the column.  
'scaler', which scales the features using StandardScaler().  
'elasticnet', which instantiates an ElasticNet() regressor.  

Specify the hyperparameter space for the  ratio using the following notation: 'step_name__parameter_name'. Here, the step_name is elasticnet, and the parameter_name is l1_ratio.

Create training and test sets, with 40% of the data used for the test set. Use a random state of 42.

Instantiate GridSearchCV with the pipeline and hyperparameter space. Use 3-fold cross-validation (This is the default, so you don't have to specify it).

Fit the GridSearchCV object to the training set.

Compute  and the best parameters. This has been done for you, so hit submit to see the results!
