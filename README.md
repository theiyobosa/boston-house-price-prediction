<h1>Boston House Prediction</h1>

<h2>Dataset</h2>

The dataset contains house prices from the real estate industry in Boston (US). The dataset contains fourteen (14) attributes. The output variable refers to the median value of owner-occupied homes in 1000 USDs.

The attributes include:

- CRIM: per capita crime rate by town
- ZN: proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS: proportion of non-retail business acres per town
- CHAS: Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX: nitric oxides concentration (parts per 10 million)
- RM: average number of rooms per dwelling
- AGE: proportion of owner-occupied units built prior to 1940
- DIS: weighted distances to five Boston employment centres
- RAD: index of accessibility to radial highways
- TAX: full-value property-tax rate per 10,000 USD
- PTRATIO: pupil-teacher ratio by town
- B: 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT: lower status of the population (%)
- MEDV: Median value of owner-occupied homes in 1000 USD's (Output/Target)

<h2>Objective</h2>

The objective is to use the first thirteen features to predict the price (MEDV) or median value of owner-occupied homes in 1000 USD's.

<h2>Libraries used</h2>

The libraries used within this repository are:

- NumPy
- Pandas
- scikit-learn
- matplotlib
- xgboost
- seaborn

<h2>Approach</h2>

Some features were joined together systematically, due to the high correlation between them. The dataset was also split, 80% of it was used for training, and the other 20% was used for testing. The model was tranined with an eXtreme Gradient Boosting regressor.

<h2>Results</h2>

The model used had an accuracy of almost 100% on the traning set, and an accuracy of 90.8% on the test set.