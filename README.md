# StockBot-Research
ARIMA-LSTM hybrid model testing on stock model prediction and DQN Learning Agent trial


PART 1 - ARIMA LSTM Model: Forecasting Stock Trends
In this section, we will retrieve multivariate data from yahoo finance and manipulate it to form our dataset that will be pre-processed, trained, and tested with an ARIMA LSTM. The output will be a graph with the final test output from the predicted values of the neural network.

Tested the final model on stocks: AAPL, CCL, SBUX, and AMZN

Part 2 - Simple DQN Learning Agent
Using the above predicted model, the closing values will  be put into the training set of the DQN agent. The agent class methods will handle when to act, buy, or sell for each epoch of testing. Then, after the reinforced learning, the model will finally test itself by outputting a graph displaying when the model buys or sells - showing the total gains at the end.
