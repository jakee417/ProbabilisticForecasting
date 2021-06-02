# ProbabilisticForecasting
## Description
Project for Stanfords Stats 271, Applied Bayesian Statistics. Implements a Variational Autoregressive LSTM with Probabilistic Layers for forecasting Cryptocurrency trade volume. Uses different Tensorflow Probability layers as Likelihood Models for the data.

## Getting Started
* `LstmRnn.py` - Tensorflow Model 
* `WindowGenerator.py` - Data loader for `LstmRnn.py`
* `layers.py` - Tensorflow Probability Likelihood models and aux. Keras layers
* `main.py` - script to invoke model
* `demo_notebook.ipynb` - `main.py` in notebook form

## Authors
* jakee417
* sandymule

## Acknowledgments

Inspiration, code snippets, etc.
* [TensorFlow Time Series](https://www.tensorflow.org/tutorials/structured_data/time_series)
* [Time2Vec](https://github.com/francois-meyer/time2vec)
* [Variational Auto Encoder](https://keras.io/examples/generative/vae/)
