# LSTM Stock Predictor

In this experiment we use a Long short-term memory (LSTM), artificial recurrent neural network to predict Bitcoin prices on the basis of the [Crypto Fear and Greed Index (FNG)]  indicator aswell as simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

> Which model has a lower loss?
FNG loss = 0.10781984031200409
Close loss = 0.033763717859983444
Clearly Close as lower loss then FNG

> Which model tracks the actual values better over time?
Close tracks actual values much better then FNG. FNG hardly tracks actual values at all, while close tracks actual values reasonably well!

> Which window size works best for the model?
The smaller the window size the better the model performs.