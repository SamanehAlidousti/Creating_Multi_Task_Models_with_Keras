# Multi-Task Models with Keras

This repository contains a Jupyter notebook demonstrating the creation and training of a multi-task neural network using the Keras library. The notebook covers topics such as dataset creation, model architecture, and training.
The model architecture includes convolutional layers, activation functions, and dense layers for both digit and color predictions. The model is compiled with appropriate loss functions and metrics for each task.

## Overview

The notebook is focused on creating a multi-task model using Keras, with tasks involving digit classification and color prediction. The model is trained on the MNIST dataset, and the architecture includes convolutional layers for feature extraction.

## Training Results
The notebook includes a custom logger to display digit and color accuracy during training. The training process is visualized using TensorBoard.

## Final Predictions
The notebook provides a function (test_model) to visualize predictions on a single test example and a grid of test examples.

## Prerequisites

Before running the notebook, ensure you have the following libraries installed:

- [TensorFlow](https://www.tensorflow.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

## Usage

1. Open the notebook in a Jupyter environment.
2. Execute the cells to import the required libraries, create the dataset, build the model, and train it.
3. The training process includes logging the accuracy for both digit classification and color prediction tasks.


