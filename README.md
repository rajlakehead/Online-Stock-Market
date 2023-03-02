# Online-Stock-Market
Data Preparation 
For this project, I pulled data on APPLE stock prices from Yahoo Finance for the five-year 
period. To train the model, I built a new data frame with only the Closing Stock Price target 
variable and transformed it into an array. The training dataset for this project contained 
75% of the values. I transformed the train and test input data into the expected structure 
using numpy.reshape(). 

Building the model and making Predictions 
Using Keras, a Long Short-Term Model was constructed to forecast the normalized closing 
stock price. It contained 50 units, 4 hidden layers, and a dense layer (output). In order to 
lower the loss or improve the algorithm, I employed the Adam optimizer. The model was 
built using the mean squared error as the loss function. Lastly, the model was calibrated and 
sent to the training features, and a test data set was made to obtain forecasts. Below I 
attached some screenshots of my outputs. 
