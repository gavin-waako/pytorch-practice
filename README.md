# PyTorch Practice

The Complete PyTorch Curriculum for learning the basics of creating and manipulating tensors to more advanced operations.

## Overview
This repository serves as a **PyTorch Practice**, helping you move from the absolute basics of tensor creation to more advanced manipulation and operations using PyTorch. Tensors are the fundamental building blocks of deep learning, and mastering them is essential for building and debugging complex neural networks. Whether you are learning as a Computer Science student or preparing for a technical career in AI/ML research, this resource will guide you on what to cover in order to master the framework.

## Tutorial Structure

### Part 1: Tensor Basics (`pytorch_practice.py`)
This module covers the essential foundations of PyTorch data structures:
* **Creating Tensors**: Initializing scalars, vectors, matrices, and multi-dimensional tensors using `torch.tensor()`.
* **Randomization**: Generating tensors with random values, including specific shapes used in computer vision, such as `[224, 224, 3]` for images.
* **Specialized Tensors**: Initializing data with `torch.zeros()`, `torch.ones()`, and creating ranges with `torch.arange()`.
* **Replication**: Using `torch.zeros_like()` to create tensors that mimic the shape of existing input data.
* **Metadata & Inspection**: Mastering the use of `.ndim`, `.shape`, `.size()`, and `.device` to inspect your data.



### Part 2: Tensor Datatypes & Precision
Deep learning performance often depends on how you manage numerical precision:
* **Float 32 vs. Float 16**: Creating tensors with specific `dtype` and converting between them using `.type(torch.float16)`.
* **Mixed Precision Operations**: Handling operations between different datatypes (e.g., multiplying `float32` by `float16`).
* **Gradient Tracking**: Introduction to `requires_grad=False` for controlling gradient computation.

### Part 3: Tensor Manipulations & Operations
Covers the fundamental mathematical operations required for model training:
* **Basic Arithmetic**: Element-wise addition, subtraction, multiplication, and division using both standard operators (`+`, `-`, `*`) and built-in functions like `torch.add()` or `torch.mul()`.
* **Scalar Operations**: Efficiently applying transformations across an entire tensor (e.g., `tensor + 100`).
* **Matrix Multiplication**: The core operation for neural network layers (Introduction to `torch.matmul`).



## Troubleshooting the "Big Three"
Based on the code covered, these are the 3 main issues you will face in PyTorch:
1. **Wrong Datatype**: Tensors must be in the correct precision (e.g., `float32`).
2. **Wrong Shape**: Aligning dimensions for operations like matrix multiplication.
3. **Wrong Device**: Verifying if tensors are on the same device (CPU vs. GPU/CUDA).

## Quick Start

### 1. Clone the repository
```bash
git clone https://github.com/gavin-waako/pytorch-practice.git
