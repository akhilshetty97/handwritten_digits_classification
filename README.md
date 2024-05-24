Handwritten Digits Classification


This repository contains code to train a neural network for classifying handwritten digits using the MNIST dataset. The MNIST dataset is a well-known dataset in the field of machine learning and computer vision, consisting of 70,000 grayscale images of handwritten digits (0-9). This project demonstrates how to preprocess the data, build and train a neural network model using TensorFlow and Keras, and evaluate the model's performance.

The MNIST dataset is loaded using Keras' built-in datasets module. The dataset is split into training and test sets.

Model Architecture:
The neural network model is defined using Keras' Sequential API. The model consists of two layers:
A dense layer with 50 neurons and ReLU activation.
An output dense layer with 10 neurons and sigmoid activation.

Training and Evaluation
The model is compiled with the Adam optimizer and sparse categorical crossentropy loss function. The training process is monitored with accuracy as the evaluation metric.
