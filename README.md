# prophet_multistock_prediction
The code imports some libraries (pandas, numpy, yfinance, and Prophet) that are used for stock price prediction.

It then creates a dictionary called my_dict that will store information about the stocks.

The mse function calculates the mean squared error between the actual and predicted stock prices.

The fit_prophet function takes in stock data as an argument and uses the Prophet library to make predictions about the future stock prices.

The tickers_file variable points to a text file that contains a list of stock tickers. The code then reads the tickers from this file and downloads the historical data for each ticker using the yfinance library.

The data is cleaned to remove any invalid or missing values, and then the Prophet library is used to fit a model and make predictions about the future prices of the stocks. The regressor_coefficients function is used to see which variables have the most impact on the stock prices. The code then uses the cross_validation function to evaluate the performance of the model by calculating the mean squared error.

Finally, the code makes future predictions for the next 60 days and stores the projected price and the last close price for each stock.
