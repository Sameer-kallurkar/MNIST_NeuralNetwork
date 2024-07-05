# Handwritten Digit Recognition Neural Network

This project implements a simple neural network in Python for recognizing handwritten digits using the MNIST dataset.

## Overview

The neural network architecture consists of:
- Input layer (784 neurons, corresponding to 28x28 pixel images)
- Hidden layer (20 neurons)
- Output layer (10 neurons, corresponding to digits 0-9)

## Implementation Details

### Files
- `data.py`: Contains functions to fetch the MNIST dataset.
- `main.py`: Implements the neural network training and inference.

### Neural Network Structure
- **Weights and Biases:**
  - `w_i_h`: Weights from input layer to hidden layer.
  - `w_h_o`: Weights from hidden layer to output layer.
  - `b_i_h`: Biases for hidden layer.
  - `b_h_o`: Biases for output layer.

### Training
- **Forward Propagation:**
  - From input to hidden layer using sigmoid activation.
  - From hidden to output layer using sigmoid activation.
- **Backpropagation:**
  - Calculates errors and adjusts weights and biases using gradient descent.

### Results
- After training for multiple epochs, the model achieves a certain accuracy on the MNIST test set.

## Usage

To run the project:
1. Ensure Python and required libraries (numpy, matplotlib) are installed.
2. Run `main.py`.

## Example

After training, you can test the model by inputting an index to visualize and predict a handwritten digit from the dataset.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

