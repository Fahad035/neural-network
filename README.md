# 🧠 Neural Network From Scratch (Build From Scratch – Season I)
🚀 Elevator Pitch

A fully functional neural network engine built entirely from scratch using only core Python and NumPy, demonstrating how modern deep learning works under the hood — without relying on any machine learning libraries.

## 📌 Project Overview

This project implements a feedforward neural network from first principles, including:

Manual forward propagation

Manual backpropagation

Gradient descent optimization

Activation functions

Loss computation

The network is trained on the classic XOR problem, proving its ability to learn non-linear patterns.

No ML frameworks used. No shortcuts. Just math, code, and fundamentals.

## 🎯 Motivation (Why This Project?)

Modern ML frameworks abstract away the inner workings of neural networks.
This project was inspired by the desire to:

Truly understand how neural networks learn

Demystify backpropagation

Build confidence in systems-level AI engineering

This aligns perfectly with the spirit of Build From Scratch – Season I.

## 🧱 Architecture Design
Network Architecture
Input (2)
  ↓
Dense Layer (2 → 4)
  ↓
ReLU Activation
  ↓
Dense Layer (4 → 1)
  ↓
Sigmoid Activation
  ↓
Output

⚙️ Components Implemented From Scratch
🔹 Dense (Fully Connected) Layer

Weight initialization

Bias handling

Forward pass

Backward pass

Gradient updates

🔹 Activation Functions

ReLU (hidden layers)

Sigmoid (output layer)

🔹 Loss Function

Mean Squared Error (MSE)

🔹 Training Engine

Manual gradient flow

Gradient descent optimization

Epoch-based training loop

🧪 Dataset
XOR Dataset

A classic non-linear classification problem:

Input X1	Input X2	Output
0	0	0
0	1	1
1	0	1
1	1	0

This dataset cannot be solved by a linear model — making it ideal for validation.

## 📈 Results

The training loss decreases consistently

Final predictions match XOR truth table

Demonstrates successful non-linear learning

Example output:

[[0]
 [1]
 [1]
 [0]]

## 🛠 Technologies Used

Language: Python

Numerical Computing: NumPy

Visualization: Matplotlib

Environment: Google Colab

ML Libraries: ❌ None

## 🧠 What I Learned

How backpropagation works at a mathematical level

Why activation functions matter

How gradients flow through a network

How neural networks learn non-linear decision boundaries

Writing clean, modular system-level code

## ⚠️ Challenges Faced

Correctly implementing gradient calculations

Debugging exploding/vanishing gradients

Managing shape consistency across layers

Ensuring numerical stability in sigmoid

Each challenge improved my understanding of deep learning internals.

## 🏆 Accomplishments

✅ Built a neural network engine from scratch
✅ No ML frameworks used
✅ Solved a non-linear classification task
✅ Fully reproducible and explainable

## 🔮 What’s Next

Add Softmax + Cross-Entropy loss

Implement mini-batch training

Add optimizers (Momentum, Adam)

Extend to multi-class classification

Build a small autograd engine

## 📂 How to Run

Open the Google Colab notebook

Run cells top-to-bottom

Observe loss convergence and predictions

## 🧾 License

MIT License — free to learn, modify, and build upon.

## 📝 Submission Description (Short Version)

This project builds a neural network entirely from scratch using only Python and NumPy. All components — dense layers, activation functions, loss computation, and backpropagation — are manually implemented without any ML libraries. The network is trained on the XOR dataset to demonstrate non-linear learning. The goal is to deeply understand and showcase how modern neural networks work internally, aligning with the spirit of Build From Scratch – Season I.
