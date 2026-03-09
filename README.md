# Micrograd-from-scratch
Implementation of a minimal automatic differentiation engine inspired by Andrej Karpathy's Micrograd to understand backpropagation and computational graphs.
# Micrograd Implementation (From Scratch)

## Overview

This project is a simple implementation of an automatic differentiation engine inspired by the Micrograd tutorial by Andrej Karpathy.
The goal of this project is to understand how neural networks compute gradients and perform backpropagation internally instead of relying entirely on high-level deep learning frameworks.

The project demonstrates how a computational graph is built and how gradients are propagated through it during training.

---

## Key Concepts Covered

* Computational Graph
* Automatic Differentiation
* Backpropagation
* Gradient Descent
* Building a simple Neural Network (MLP)

---

## Implementation Details

The notebook implements the core idea behind automatic differentiation by creating a custom `Value` class that stores data and gradients.

Basic mathematical operations such as addition, multiplication, and activation functions are implemented while maintaining the computational graph structure. This allows gradients to be calculated automatically during backpropagation.

The project also demonstrates how neurons, layers, and multi-layer perceptrons can be built using these primitives.

---

## Technologies Used

* Python
* Jupyter Notebook
* Basic deep learning concepts

---

## Learning Outcome

Through this project, I gained a deeper understanding of how modern deep learning frameworks compute gradients and perform backpropagation under the hood.

Instead of treating frameworks as black boxes, this project helped me understand the internal mechanics of neural network training.

---

## Reference

Inspired by the educational work of Andrej Karpathy and the Micrograd project.
