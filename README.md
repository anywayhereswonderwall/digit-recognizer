# Handwritten Digit Recognition using only NumPy

![Python](https://img.shields.io/badge/python-3.8%2B-blue)
![NumPy](https://img.shields.io/badge/numpy-1.20.0-green)


## Dataset

The project uses the MNIST dataset, a widely used dataset containing 28x28 grayscale images of handwritten digits (0-9).

## Model Architecture

The digit recognition model consists of a simple neural network architecture:

- Input layer (784 units, corresponding to the flattened 28x28 image)
- 2 hidden layers (20 units each, Relu activation)
- Output layer (10 units, softmax activation)

## Training

The model is trained using Adam optimization algorithm with learning rate decay.

## Evaluation

The trained model is evaluated using a separate test set from the MNIST dataset. The accuracy of the model on the test set is used as the primary evaluation metric.