# Machine-Learning-for-Data-Mining
Implementing different validation methods and comparing their performances

We will be analyzing crime rate data from different communities. The original data set can be found
on the UCI machine learning data repository (https://archive.ics.uci.edu/ml/datas
ets/Communities+and+Crime+Unnormalized). This data set consists of many attributes of
different communities, such as household size, percentage of race of different groups, number
of police officers, etc. The goal is to use these attributes to predict the total number of nonviolate crimes (per 100k population). The original data set consists of 2215 observations, 129
predictors and 18 different response variables. I have again done the honors to clean up the
data, which included removing predictors with missing values and removing the unnecessary
response variables. The final data set that you will use (community.csv) consists of 2118
observations, and 101 predictors + 1 response (total number of non-violent crimes).

The main task is to create a Lasso regression model that uses the 101
predictors to predict the total number of non-violent crimes. In particular, you will need to
implement the following three methods to determine the best hyperparameters to use:
1. Train / validation / test split.
2. 5-Fold cross validation.
3. 10-Fold cross validation

This is a typical application of the Lasso penalty. In many applications, especially with
high dimensional data (too many predictors, too few observations), a first step is to screen
out useless features, and Lasso is an excellent tool for that.

Developed by:

Hema Vivekanandan: https://github.com/Hema23294

Mukul Pathak: https://github.com/pathakmukul
