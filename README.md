# Neural Network Classification with PyTorch: Linear vs. Non-linear

This notebook demonstrates the difference between linear and non-linear classification using PyTorch.  It uses the `make_circles` dataset from scikit-learn to visualize the concepts.

## Overview

The notebook covers the following steps:

1. **Data Preparation:** Generates a circular dataset, visualizes it, and converts it to PyTorch tensors.  The data is then split into training and testing sets.

2. **Linear Model:** Builds a simple neural network with linear layers and trains it on the circular data.  The limitations of a linear model for this type of data are shown.

3. **Non-linear Model:** Introduces non-linearity using ReLU activation functions within the neural network. This allows the model to learn complex, non-linear decision boundaries. The improved performance on the circular dataset is demonstrated.

4. **Visualization:**  The decision boundaries for both the linear and non-linear models are plotted to visually highlight the impact of non-linearity.
