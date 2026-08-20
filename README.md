# NASA-CMAPSS-RUL-Prediction
Predicting the remaining useful life of turbofan engines using deep learning and NASA C-MAPSS dataset


7th semester project using the data from the NASA C-MAPSS FD001 project. The prime target of this project is to predict the Remaining Useful life (RUL) of the turbofan engines for specific application from a sensor data input.

In this project, comparing 4 deep learning models:

LSTM
GRU
1D-CNN
Transformer

The models utilize a 30 cycle snapshot of the sensor information to make a prediction for how many cycles the engine will last until failure.

The different models are then compared in terms of RMSE and the NASA scoring function to determine which model works best.

1D-CNN gave better performance compared with the recurrent models and the Transformer gave the highest performance within the 4 models.
Best Model: Transformer
Test RMSE: 15.47
NASA Score: 452.6
