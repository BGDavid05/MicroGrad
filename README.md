# MicroGrad
Mini Neural Network Project

# 🤖 Neural Network Engine

A simple yet powerful Neural Network Engine implemented in Python from scratch. This project provides a basic framework for automatic differentiation and building neural networks using custom classes.

## 🚀 Features

+ 🔢 Custom Autograd Engine for backpropagation.

+ 🔗 Value Class for tracking operations and gradients.

+ 🧠 Multi-Layer Perceptron (MLP) implementation.

+ ⚡ ReLU Activation for non-linearity.

+ 🏗️ Modular Design with Neurons, Layers, and Models.

## 🛠️ Technologies Used

+ Python for the core implementation.

+ NumPy for numerical operations.

+ Matplotlib (planned) for visualization.

## Training a neural net
The notebook `demo.ipynb` provides a full demo of training an 2-layer neural network (MLP) binary classifier. This is achieved by initializing a neural net from micrograd.nn module, implementing a simple svm "max-margin" binary classification loss and using SGD for optimization. As shown in the notebook, using a 2-layer neural net with two 16-node hidden layers we achieve the following decision boundary on the moon dataset:
![image](https://github.com/user-attachments/assets/46b3e00f-e4dd-4285-b10e-d658727e5cdc)
