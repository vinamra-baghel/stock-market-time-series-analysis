# Stock_Market_Analysis_using_ML

This is our Summer Project under which we have to predict stock prices using various models like
Linear Regression, LSTM, and ARIMA model for any data set.

We have to make a Stock Market Prediction Model using Machine Learning, by first taking the data provided (here, GOOGLE and initially Tesla)
and checking the basic database along with performing an explanatory data analysis on the training set by plotting various plots and 
correlation graphs, and finally branching towards the three ML algorithms:-

Linear Regression: For the target variable "Close", separated out the train and test dataset using the train_test_split method under sklearn
and plotted the actual data with the prediction based on both the test and train dataset using the LinearRegression library of clean and 
calculated the rmse for score evaluation.

LSTM(Long Short Term Memory): Using the "close" variable as training data and scaler "min-max", first converted the test, 
and train data to a NumPy array over which we created the LSTM model by adding 3 layers using Sequential() library of Keras 
and compiled the model by using optimizer='adam', loss='mean_squared_error' and fitted data into it using x_train,y_train, 
epochs,batch_size, verbose, Next thing was to load the test data and predict values accordingly and calculated the rmse for 
score evaluation with a prediction for next 10 days.

ARIMA: Starting with installing pmdrima in our colab notebook and inserting the train data the, first thing to do here was, 
to do the fuller test to get the "p-value" for auto-regression, which we got here above 0.05, showing us that a potential 
difference of data is needed which again was verified via the stepwise_fit auto_arima command where we found the model to be 
(1,1,0):(p,q,r), moving on to fitting the p,q,r to the model and plotting for predictions and calculated the rmse for score evaluation,
Next thing was to load the test data and predict values accordingly and calculated the rmse for score evaluation with a prediction for 
next 10 days.

