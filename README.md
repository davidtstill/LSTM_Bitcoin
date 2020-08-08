# LSTM_Bitcoin

The analysis attempts to model bitcoin closing prices utilizing deep learning recurrent neural networks. The first model
uses a window of closing prices to predict the nth closing price. The second model uses the Crypto Fear and Greed Index (FNG), a daily index that analyzes the sentiment of the Bitcoin/crypto market, to predict the closing price. 

Both models build and train a custom LSTM RNN using a 10 day window of Bitcoin either closing prices or fear and greed index values to predict the 11th day closing price. In both models the overview follows this sequence:

- Prepare the data for training and testing
- Build and train a custom LSTM RNN
- Evaluate the performance of the model

Importantly, both models use the same model architecture and radmon seed to accurately compare the peformance of the closing price model vs the FNG model. 

Ultimately the closing price model does a better job of predicting future values.
