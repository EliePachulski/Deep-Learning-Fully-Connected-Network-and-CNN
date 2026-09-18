# Deep Learning – Fully Connected Networks & Convolutional Neural Networks

This repository contains my solution for the first Deep Learning assignment at the Technion – Israel Institute of Technology.

The project focuses on implementing neural networks from both a theoretical and practical perspective. It covers manual implementation of a fully connected neural network as well as the design and training of a convolutional neural network (CNN).

---

## Project Overview

The assignment is divided into four main parts:

### Part 1 – Neural Network Theory
- Analysis of small neural networks.
- Expressing networks as well-known mathematical functions.
- Derivation of activation function gradients.
- Derivation of the Softmax and Cross-Entropy gradients.

### Part 2 – Fully Connected Neural Network (MNIST)

A complete feed-forward neural network was implemented **from scratch** using only PyTorch tensor operations.

Implemented components include:

- Forward propagation
- Backpropagation
- Sigmoid activation
- Softmax output layer
- Cross-Entropy loss
- Gradient Descent optimization
- Weight initialization
- Training and evaluation loops
- Learning rate comparison

The implementation intentionally avoids:

- `torch.nn`
- Automatic differentiation (`backward()`)
- Built-in optimizers
- Built-in loss functions
- Built-in activation functions

### Part 3 – Learning Rate Analysis

The fully connected model is trained using multiple learning rates in order to compare:

- Convergence speed
- Training loss
- Test loss
- Training accuracy
- Test accuracy

### Part 4 – Convolutional Neural Network

A custom CNN was designed and trained from scratch to classify **10 species of big cats**.

The model includes:

- Convolutional layers
- Batch Normalization
- ReLU activations
- Max Pooling
- Dropout
- Global Average Pooling
- Adam optimizer
- Learning-rate scheduling
- Data augmentation

Performance is evaluated on separate training, validation and test sets.

---

## Technologies

- Python
- PyTorch
- TorchVision
- NumPy
- Matplotlib
- Google Colab

---

## Repository Structure

```
├── HW1_340868488_340872084.ipynb    # Complete implementation
├── DL_Fully_Connected_CNN.pdf       # Assignment instructions
└── README.md
```

---

## Topics Covered

- Neural Networks
- Backpropagation
- Gradient Descent
- Softmax
- Cross Entropy
- Fully Connected Networks
- Convolutional Neural Networks
- Batch Normalization
- Dropout
- Data Augmentation
- Hyperparameter Tuning
- Computer Vision
- Image Classification

---

## Results

The project demonstrates both the mathematical foundations and practical implementation of modern neural networks, progressing from manually implementing backpropagation on MNIST to building and training a custom CNN for image classification.
