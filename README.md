# 🧠 Two-Layer Neural Network from Scratch (NumPy)

## 📌 Project Overview

This project demonstrates the implementation of a **two-layer neural network from scratch using NumPy**, without relying on high-level deep learning frameworks such as TensorFlow or PyTorch.

The goal of this project is to **build a strong foundation in machine learning by understanding how neural networks work internally**, including forward propagation, backpropagation, and gradient descent.


---

## 🏗️ Neural Network Architecture

The model uses a simple **2-layer neural network**:


### Architecture Details
- Input layer: Feature matrix `X`
- Hidden layer:
  - Linear transformation
  - `tanh` activation
- Output layer:
  - Linear transformation
  - `sigmoid` activation
- Loss function: Binary Cross-Entropy (Log Loss)
- Optimizer: Gradient Descent

---

## ⚙️ Key Features

- Implemented completely using **NumPy**
- Manual forward propagation
- Manual backpropagation using chain rule
- Gradient descent optimization
- Cost monitoring during training
- Clean and modular function-based design
- Beginner-friendly and educational

---

The notebook contains:
- Dataset creation and preprocessing
- Parameter initialization
- Forward propagation
- Cost computation
- Backpropagation
- Parameter updates
- Model training loop

---

## 🧪 Training Configuration

- Hidden units: Configurable (e.g., `n_h = 2`)
- Learning rate: Tunable (e.g., `1.2`)
- Number of iterations: 3000+
- Weight initialization: Small random values
- Bias initialization: Zeros

---

## 🧮 Mathematical Concepts Used

### Linear Transformation

### Activation Functions
- `tanh`
- `sigmoid`

### Binary Cross-Entropy Loss

### Optimization
- Gradient descent
- Chain rule for backpropagation

---

## 📈 Output

After training, the model outputs:
- Learned parameters:
  - `W1`, `b1`
  - `W2`, `b2`
- Training cost (optional printing)

This confirms successful convergence of the neural network.

---



