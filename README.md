# Deep Learning Initialization Techniques

This repository contains practical implementations of different parameter initialization methods for Deep Neural Networks, completed as part of deep learning coursework. Proper initialization plays a crucial role in breaking symmetry, preventing vanishing/exploding gradients, and ensuring faster convergence.

##  Implemented Methods

1. **Zero Initialization (`initialize_parameters_zeros`)**
   * Initializes all weights and biases to zeros.
   * Demonstrates the **symmetry breaking failure**, showing why the model fails to learn effectively when all neurons compute the same functions.

2. **Random Initialization (`initialize_parameters_random`)**
   * Initializes weights to large random values (scaled by 10) and biases to zeros.
   * Demonstrates the effects of large initial weights on deep networks.

3. **He Initialization (`initialize_parameters_he`)**
   * Initializes weights using He initialization (`sqrt(2 / prev_layer_dims)`) and biases to zeros.
   * Highly recommended for layers with **ReLU** activation functions to maintain variance across layers and stabilize training over thousands of iterations.

##  Tech Stack
* **Python**
* **NumPy**
* **Deep Learning / Neural Networks fundamentals**
