# MLP Handwritten Digit Classification

## Overview
This notebook demonstrates the implementation of a simple neural network using NumPy and manual backpropagation. The goal is to understand the inner workings of neural networks by manually coding the forward and backward passes.

## Steps

### 1. Data Preparation
- **Data Loading**: Loaded the dataset and prepared the input features and target labels.
- **Normalization**: Normalized the input data to ensure that the features have similar scales, which helps in faster convergence.

### 2. Network Initialization
- **Weights and Biases**: Initialized the weights and biases for each layer of the neural network. The weights were initialized randomly, and the biases were initialized to zero.

### 3. Forward Pass
- **Linear Combination**: Computed the linear combination of inputs and weights for each layer.
- **Activation Function**: Applied the activation function (e.g., sigmoid, ReLU) to introduce non-linearity into the model.

### 4. Loss Calculation
- **Loss Function**: Used a loss function (e.g., Mean Squared Error, Cross-Entropy) to measure the difference between the predicted outputs and the actual target values.

### 5. Backward Pass (Backpropagation)
- **Gradient Calculation**: Calculated the gradients of the loss with respect to the weights and biases using the chain rule.
- **Weight Updates**: Updated the weights and biases using the calculated gradients and a learning rate.

### 6. Training Loop
- **Epochs**: Repeated the forward and backward passes for a specified number of epochs.
- **Performance Monitoring**: Monitored the training and validation accuracy and loss to ensure the model is learning effectively.

## Conclusion
By manually implementing backpropagation with NumPy, I gained a deeper understanding of how neural networks learn and update their parameters. This foundational knowledge is crucial for understanding more complex deep learning frameworks.
