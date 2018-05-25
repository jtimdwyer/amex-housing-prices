# House Prices in Ames Iowa

In this repository I build a model to predict the price of homes in Ames Iowa. To this end I used the Python modules, Pandas and Seaborn to process and examine the data and SKLearn to create and evaluate regression models based on this data. The original data, and the data stored at different stages in my work, can be found [here](./data/). The training data contained 2051 observations, each with 80 features (including the sale price of the home).

## Structure
These sections should be read in sequence but you may just read the summary at the end if you wish.

1. [Data Cleaning and Exploration](./notebooks/1_cleaning.ipynb)
> Missing data from the training and test sets are determined and outliers and erroneous data is removed.

2. [Feature Engineering & Selection](./notebooks/2_eda_engineering.ipynb)
> Features are dropped due to low correlation or variance. Converting categorical information to numerical using dummy variables. Some variables are transformed to remove skew.

3. [Modeling](./notebooks/modeling.ipynb)
> Fit and score Linear Regression models with Lasso, Ridge and Elastic Net penalties. Models are stored as `pickle` files in the [data directory](./notebooks/pickled_models)

4. [Summary](./summary.md)   
> A summary of results, methodology and technologies used.
