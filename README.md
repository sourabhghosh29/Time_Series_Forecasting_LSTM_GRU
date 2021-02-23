# Time_Series_Forecasting_LSTM_GRU
### Timeseries Forecasting & Model Performance Comparison for US Liquor Sales (1980-2007)
#### Comparing change across (Feed Forward Neural Network ,Back Propagation Through Time, LSTM, GRU)

Model Performance Comparison (FNN,BPTT,LSTM,GRU)
For comparing model performance across different networks we will consider 2 types of comparison :
1.Qualitative(Least MSE) : Determining which model reaches a competitive MSE across when trained across same number of epochs and batch size. The modelcoverging faster to the minimum mse will be rated higher.
2.Computational Effort : The model taking lesser amount of time to build, resulting lesser mse score will be rated higher in this type.
We will decide the best model for this problem statement based on the tradeoff between the above two scenarios

Conclusion :
Looking at the two types of performance comparison we can conclude reaching a trade off that LSTM model performs decent holding second position in bothcomparison types. Hence we can choose LSTM as best model for this problem statement of forcasting Liquor Sales in United States between 1980 to 2007 sales data

### Please refer report file for detailed analysis and conclusion

References :
https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM (https://www.tensorflow.org/api_docs/python/tf/keras/layers/LSTM)
https://machinelearningmastery.com/time-series-prediction-lstm-recurrent-neural-networks-python-keras/ (https://machinelearningmastery.com/time-series-predictionlstm-
recurrent-neural-networks-python-keras/)
https://adventuresinmachinelearning.com/recurrent-neural-networks-lstm-tutorial-tensorflow/ (https://adventuresinmachinelearning.com/recurrent-neural-networks-lstmtutorial-
tensorflow/)
https://medium.com/@erikhallstrm/hello-world-rnn-83cd7105b767 (https://medium.com/@erikhallstrm/hello-world-rnn-83cd7105b767)
https://intellipaat.com/community/25190/record-the-computation-time-for-each-epoch-in-keras-during-model-fit (https://intellipaat.com/community/25190/record-thecomputation-
time-for-each-epoch-in-keras-during-model-fit)
