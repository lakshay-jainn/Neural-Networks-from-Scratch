# Neural Network from Scratch (MNIST Classifier)

This project implements a fully connected neural network **from scratch in Python**, without using deep learning libraries such as TensorFlow or PyTorch. The goal was to understand how neural networks work under the hood by building everything manually — from the math to the code.

## Project Overview
- Implemented a neural network with:
  - **784 input neurons** (MNIST image pixels)
  - **256 hidden neurons**
  - **10 output neurons** (digit classes 0–9)
- Wrote out **every derivative for backpropagation from scratch**, starting with single-sample updates and then generalizing to full matrix form.
- Implemented core components manually:
  - Data normalization
  - Weight initialization
  - Activation functions (Sigmoid, ReLU, Softmax)
  - Forward pass
  - Backward pass (backpropagation)
  - Loss function (Cross-Entropy)
- Achieved **90.6% accuracy** on unseen MNIST test data.

## Key Learnings
- Built intuition about how activations affect decision boundaries and how gradient descent optimizes parameters.
- Connected **geometric intuition → mathematical derivation → implementation in code**.
- Gained deeper insight into what happens behind the scenes in high-level frameworks like TensorFlow and PyTorch.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/neural-net-from-scratch.git
   cd neural-net-from-scratch


<video src="https://github.com/user-attachments/assets/27bd2d73-18e1-4cc1-a699-53b2e50c37aa" >
</video>

