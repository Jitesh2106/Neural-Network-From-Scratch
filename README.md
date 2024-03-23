# Neural Network Implementation

This repository contains an implementation of a simple neural network from scratch using Python. The neural network is implemented with classes for various layers and loss functions.

## Requirements
- Python 3.x
- NumPy
- Matplotlib
    
## Implemented Layers
1. **LinearTransform**: Represents a layer that performs a linear transformation on the input.
2. **ReLU**: Represents the Rectified Linear Unit activation function.
3. **SigmoidCrossEntropy**: Represents the Sigmoid Cross-Entropy loss function.

## Neural Network Class
- `Net`: Represents the neural network class which integrates the layers and loss function to perform training and evaluation.

## Training and Evaluation
The neural network is trained using mini-batch gradient descent with backpropagation. After each epoch, the training and testing error rates are calculated and displayed.

## Results Visualization
The error rates during training and testing are visualized using Matplotlib to understand the performance of the neural network over epochs.

