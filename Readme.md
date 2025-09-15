# XOR Neural Network - PyTorch

This repository contains a Jupyter Notebook that demonstrates how to solve the classic XOR problem using a simple neural network built with PyTorch. The XOR problem is a fundamental example in machine learning, illustrating the need for non-linear models and hidden layers.

## Table of Contents

- [Overview](#overview)
- [XOR Problem](#xor-problem)
- [Neural Network Solution](#neural-network-solution)
- [How to Run](#how-to-run)
- [Results](#results)
- [Author](#author)

## Overview

The notebook walks through:
- Creating a noisy XOR dataset
- Building a neural network with one hidden layer
- Training the model and visualizing its decision boundaries
- Experimenting with different numbers of neurons in the hidden layer

## XOR Problem

The XOR ("exclusive OR") function outputs 1 if the two binary inputs are different, and 0 if they are the same. It is not linearly separable, meaning simple models like a single-layer perceptron cannot solve it.

| Input A | Input B | A XOR B |
| ------- | ------- | ------- |
| 0       | 0       | 0       |
| 0       | 1       | 1       |
| 1       | 0       | 1       |
| 1       | 1       | 0       |

## Neural Network Solution

The notebook uses PyTorch to build a feedforward neural network with:
- An input layer (2 features)
- One hidden layer (with 1, 2, or 3 neurons)
- An output layer (1 output, using sigmoid activation)

It shows how increasing the number of neurons in the hidden layer allows the network to learn the XOR function.

## How to Run

1. Clone this repository:
    ```sh
    git clone https://github.com/yourusername/xor-nn-pytorch.git
    cd xor-nn-pytorch
    ```
2. Install dependencies:
    ```sh
    pip install torch numpy matplotlib
    ```
3. Open the notebook:
    ```sh
    jupyter notebook XOR-NN.ipynb
    ```
4. Run the cells to see the data, training process, and decision boundaries.

## Results

- With 1 hidden neuron: The network cannot solve XOR.
- With 2 or more hidden neurons: The network learns to separate the XOR classes.
- Decision boundaries and training curves are visualized for each case.

## Author

- Yasin Pourraisi  
  - [GitHub](https://github.com/yasinpurraisi)  
  - Email: yasinpurraisi@gmail.com  
  - Telegram: @yasinprsy

---

Feel free to fork, modify, and use this notebook as a starting point for learning neural networks and PyTorch!