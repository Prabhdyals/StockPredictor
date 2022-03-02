# LSTM Stock Predictor

Used deep learning recurrent neural networks to model bitcoin closing prices. One model used the FNG indicators to predict the closing price while the second model used a window of closing prices to predict the nth closing price.


1. Prepared-the-data-for-training-and-testing
2. Built-and-trained-custom-lstm-rnns
3. Evaluated the performance of each model


### Files

[Closing Prices Starter Notebook](lstm_stock_predictor_closing.ipynb)

[FNG Starter Notebook](lstm_stock_predictor_fng.ipynb)


#### Data Prep for Training and Testing


* Used the FNG values to predict future closing prices. 
* Used the past closing prices to predict future closing prices. 
* Appled the MinMaxScaler to the X and Y values to scale the data for the model. 
* Reshaped X_train and X_test to fit the model requirements (samples, time steps, features). 

#### Built and trained custom LSTM RNNS 

* Created a notebook to fit the data using FNG Values.
* Created a notebook to fit the data using closing prices. 

#### Evaluated Model Performance  

* Determined which model had the lowest loss. 
* Determined which model tracks the actual values best over time. 
* Determined the appropriate Window Size for the model. 




