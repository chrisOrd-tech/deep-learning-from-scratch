# Deep Learning from Scratch (NumPy)

This repository demonstrates how to build and train a deep neural network from first principles using only **NumPy**, without relying on deep learning frameworks such as `PyTorch` or `TensorFlow`.

The model is trained and evaluated on the **MNIST handwritten digits dataset**.

## What This Project Covers

- Manual implementation of a fully connected deep neural network
- Forward and backward propagation using matrix calculus
- Gradient computation and parameter updates
- ReLU activation and cross-entropy loss
- Training and evaluation on MNIST using NumPy only

No automatic differentiation, no high-level abstractions, every operation is explicitly implemented.

## Tech Stack

- Python
- NumPy
- Jupyter Notebook

## Project Structure

- data/ — MNIST compressed data
- utilities/ — helper functions to load MNIST datasets

## Notes

- This is not a production-ready training framework.
- The focus is on understanding the mathematics and mechanics of deep neural networks.
- All computations are performed on CPU using NumPy.