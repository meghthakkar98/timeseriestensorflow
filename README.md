# Time Series Forecasting using Deep Learning Models

## Overview

This project showcases the development of a sophisticated predictive model for time-series forecasting, leveraging advanced deep learning techniques. Utilizing TensorFlow and Keras, the project demonstrates a comprehensive approach from data preprocessing and exploratory data analysis (EDA) to the implementation of a complex neural network architecture.The goal of the project is to apply deep learning to do time series classification. Specifically, we will use a dataset slightly modified from the LSST dataset (used in 2018 Kaggle competition "Photometric LSST Astronomical Time Series Classification Challenge (PLAsTiCC)").

## Key Features

- **Data Processing**: Rigorous EDA and preprocessing to prepare a large dataset for model input.
- **Neural Network Design**: A custom neural network architecture incorporating Bidirectional GRU, LSTM, and SimpleRNN layers, optimized with techniques like EarlyStopping and ReduceLROnPlateau.
- **Model Optimization and Testing**: Strategies for model improvement through data balancing and insightful visualization of training progress. Comprehensive testing on unseen data to validate model effectiveness.

## Technologies Used

- Python
- TensorFlow
- Keras
- Pandas & NumPy for data manipulation
- Matplotlib & Seaborn for data visualization

## Model Architecture

The model employs a sequential layer setup with a focus on temporal data processing, suitable for handling time-series data. The architecture is detailed with layer configurations and the rationale for choosing specific layers and regularization techniques.


## Results

The project culminates in a model capable of accurately forecasting categorical outcomes from time-series data, validated against an unseen test set. The rigorous testing phase demonstrates the model's robustness and reliability in predicting time-series events. Performance metrics, visualized through graphs and tables, highlight the model's precision and recall, offering a transparent view of its forecasting abilities.



