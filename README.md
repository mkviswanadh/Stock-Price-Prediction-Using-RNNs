# Stock-Price-Prediction-Using-RNNs
Stock Price Prediction Using RNNs

#### Observations from Raw Data
1. Total of 4 Stocks Amazon, Google, Microsoft & IBM
2. All the Stock files have equal number of records 3019 except IBM which has 3020 records
3. All the Open, Close, Low & High Stock Prices are with in the ranges of 15 to 1200
4. IBM has lower stock volume & Microsoft has higher stock volume than other companies
5. Stock Volumes are High in 2008 & gradually showing decreasing trend towards 2018


#### Models & Evaluation
1. Close Stock Price feature used for Prediction
2. As a first Step Simple or Vanilla Sequential RNN has been used with 1 dense layer and default parameters
3. Optimized the Sequential with Hyper Tunning using various combinations of activation functions, Units, dropout rates & learning rate
4. Further optimized using Advanced RNN model Long Short Term Memory (LSTM) model to increase the Regression performance
5. Further optimized using Advanced RNN model Gated Recurrent Unit (GRU) model to increase the Regression performance
6. mean_squared_error considered as evaluation metric for Regression

#### RNN Evaluation Metrics
1. Optimized Sequential RNN given test loss of 0.054 & RMSE 0.28
2. Optimized LSTM Model given test loss of test loss of 0.057 & RMSE 0.23
3. Optimized GRU Model given test loss of 0.0579 & RMSE 0.24
4. Plotted the Test Loss & Prediction metrics after each evaluation
5. One common thing noticed irrespective of changing various Hyper Parameters & did grid search results are almost close
