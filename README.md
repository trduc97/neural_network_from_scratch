This repo includes 2 implementations for multi-class classification purposes:

(1) Using a multi-perceptrons approach

(2) Using a multi-layer dense neural network 

Metric: F1_score, accuracy, precision, recall 

Dataset: vehicles and infrastructure satellite images from the [Overhead-MNIST]([url](https://arxiv.org/pdf/2102.04266)) dataset, which is a much more challenging implementation compared to the original digit MNIST.

The Neural network implementation includes both sigmoid and relu activation for the hidden layer, a flexible number of hidden layers, a momentum learning rate, and a learning rate scheduler. 

**Results (F1-score)**

- Perceptron: **0.34/1.00**

- Dense Neural Network*: **0.65/1.00**

  *{'relu':[512,128,64,32]}

![result_table](https://github.com/trduc97/neural_network_from_scratch/assets/52210863/8b563fd2-2990-4208-bc2c-d0a96a4a8fca)

Both of the models use the numpy library to perform calculations, with an option to include the expit function from the scipy library for more complex input as this is a more stable implementation of the sigmoid function, although the expit was imported, it was not utilized in this implementation
