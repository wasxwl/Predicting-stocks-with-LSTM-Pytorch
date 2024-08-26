# LSTM-PyTorch
It used the Yahoo Finance to get FTSE data from 2000 to 2023, then use 85% split ratio to get train data and test data, then use Epoches=5 and learning rate=0.8 to train the pytorch LSTM model, then use trained model to predict the test data.

You can change the COMPANY_TICKER to the other symbol to get the other stock data, you can also change the start date and end date to change the date range, you can also change the other hyper parameters, such as Epoches, learning rate...



## Requirements
* Python 3.10 <br/>
* matplotlib 3.7.2<br/>
* numpy 1.22.3<br/>
* scikit-learn 1.0.2<br/>
* torch 2.0.1<br/>
* yfinance 0.2.28<br/>

It suggests to use conda to create the virtual environment first, then use pip install -r requirements.txt to install the dependent libraries, for example
1. conda create -n "lstm-stock" python=3.10.0    
2. conda activate lstm-stock
3. pip install -r  requirements.txt                                                                                                                                                                                                     
                                                                         