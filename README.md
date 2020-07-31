# bike-share-demand

This dataset was retrieved from kaggle.

purpose of this project is: preform a linear regression model to predict the number of bicycles rented on a givin day

dataset includes the folowing features
- hourly observations
- weather forcast for every hour
- if day is a weekend or holiday
- distinguishis between registered and nonmember riders
- season

visualizations were created with seaborn

polynomials and interactions were created with PolynomialFeatures from sklearn

data was standardized with standardScaler from sklearn

used train_test_split from sklearn to split the data for model testing

used three models:
- DummyRegressor as baseline model
- LinearRegression
- LassoCV


1. Transform all data to proper datatypes
2. create visualizations to observe trends and outliers
3. remove features with colinearity
4. standardize the data
5. split data to test model fitting
6. create baseline model with basic features
7. advance to more sophisticated models
8. reach conclusion


conclusions;
- incetivize membership
- preserve a cushion of 200 bicycles as rmse suggests
- promote summer riding 