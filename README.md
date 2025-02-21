# WhethertheWeather
 Quantum Time Series Forecasting the Weather

Using the [Jena Climate](https://www.kaggle.com/datasets/mnassrib/jena-climate) Dataset to test the model and compare it's performance to a classical model. Unfortunately I forgor how exactly accuracy is measured for timeseries predictions.

`QWeather-LSTM` has not been trained on the dataset as I have yet to figure out how to implement a Quantum LSTM that doesn't take ages to train. I also need NVIDIA GPU with CuQuantum to run the pennylane `lightning.gpu` device with `MPI`.
