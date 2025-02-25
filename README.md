# ml
# 1 - import our dataset
# from sklearn.datasets import load_diabetes
# X, y = load_diabetes(return_X_y=True)

# 2 - preprocess
# we will use only one feature -----X = X[:,[2]]

# 3 - traing our model
# training  ---from sklearn.model_selection import train_test_split
# X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, shuffle=False)

# 4 - apply linear regression
# from sklearn.linear_model import  LinearRegression
# regressor = LinearRegression().fit(X_train, y_train)
# regressor.coef_    /    regressor.intercept_

# 5 - write our model  ------ y = 152.05351614434244 + 957.76202681*x

# 6 - evaluate our model (metrics: mse, rmse, r2) --------from sklearn.metrics import mean_squared_error, r2_score, mean_absolute_error
# plot results
