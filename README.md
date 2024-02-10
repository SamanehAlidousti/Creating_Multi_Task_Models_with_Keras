# Multi-Task Models with Keras

This repository contains a Jupyter notebook demonstrating the creation and training of a multi-task neural network using the Keras library. The notebook covers topics such as dataset creation, model architecture, and training.

## Overview

The notebook is focused on creating a multi-task model using Keras, with tasks involving digit classification and color prediction. The model is trained on the MNIST dataset, and the architecture includes convolutional layers for feature extraction.

## Prerequisites

Before running the notebook, ensure you have the following libraries installed:

- [TensorFlow](https://www.tensorflow.org/)
- [NumPy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)

## Usage

1. Open the notebook in a Jupyter environment.
2. Execute the cells to import the required libraries, create the dataset, build the model, and train it.
3. The training process includes logging the accuracy for both digit classification and color prediction tasks.

```python
# Example code snippet
%matplotlib inline
%load_ext tensorboard
import tensorflow as tf
import numpy as np
import matplotlib.pyplot as plt
import shutil

# ... (rest of the code)
