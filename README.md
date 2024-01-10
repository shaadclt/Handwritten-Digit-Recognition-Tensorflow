# Handwritten Digit Recognition using TensorFlow

This project focuses on building a neural network using TensorFlow to recognize handwritten digits from the MNIST dataset. The model is a simple feedforward neural network with one hidden layer.

## Getting Started

### Prerequisites
- [TensorFlow](https://www.tensorflow.org/install)
- [Matplotlib](https://matplotlib.org/stable/users/installing.html)

### Installation
```bash
pip install tensorflow matplotlib
```

## Usage
1. Open the Jupyter Notebook file **ANN_MNIST.ipynb**.
2. Run the notebook cell by cell to execute the code.
3. Visualize the loss and accuracy graphs to evaluate the model's performance.


## Dataset
The MNIST dataset is a collection of 28x28 pixel grayscale images of handwritten digits (0 through 9). It is a widely used dataset for machine learning and computer vision tasks.


## Model Architecture
The neural network consists of:

- Input layer: Flatten layer to convert the 28x28 images into a flat vector.
- Hidden layer: Dense layer with ReLU activation function and dropout for regularization.
- Output layer: Dense layer with softmax activation for digit classification.


## Training the Model
Train the model on the training data and evaluate it on the test data.


## Visualizing Results
Visualize the training and validation loss, as well as training and validation accuracy, over epochs.
