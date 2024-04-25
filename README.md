This repo include 2 implementation for multi-class classification purpose:

(1) Using a multi-perceptrons approach

(2) Using a multi-layer dense neural network 

Metric: F1_score, accuracy, precision, recall 

Dataset: vehiles and infastructure satelite images from the [Overhead-MNIST]([url](https://arxiv.org/pdf/2102.04266)) dataset, which is a much more challenging implementation compare to the original digit MNIST.

The Neural network implementation include both sigmoid and relu activation for the hidden layer, flexible number of hidden layers, and momentum learning rate, along with a learning rate scheduler. 

Multi-class classification results (F1-score)

Perceptron: **0.34/1.00**

Dense Neural Network*: **0.65/1.00**
*{'relu':[512,128,64,32]}
