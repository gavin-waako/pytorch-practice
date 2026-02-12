# PyTorch Learning Tutorial

A comprehensive PyTorch tutorial designed for learning and interview preparation.

## Overview
This tutorial covers PyTorch fundamentals through advanced topics commonly asked in machine learning engineer interviews. It bridges the gap between basic tensor manipulation and the complex architectural implementations required for senior ML roles.

## Tutorial Structure

### Part 1: Tensor Basics (`01_tensor_basics.py`)
Based on the foundational exercises in `pytorch_practice.py`:
* **Creating and manipulating tensors**: Initializing scalars, vectors, matrices, and multi-dimensional tensors using `torch.tensor()`.
* **Basic operations and broadcasting**: Performing element-wise addition, subtraction, and multiplication.
* **Randomization & Images**: Generating random tensors and image-like structures (e.g., `[224, 224, 3]`).
* **Metadata & Precision**: Inspecting `.shape`, `.ndim`, and managing `dtype` (float32 vs. float16).
* **Device Management**: Handling tensors on CPU vs. GPU/CUDA.



### Part 2: Autograd and Gradients (`02_autograd_gradients.py`)
* **Automatic differentiation**: Understanding how PyTorch tracks operations.
* **Gradient computation**: Using `.backward()` to compute slopes.
* **Gradient flow control**: Using `requires_grad=False` to freeze layers during training.
* **Common interview scenarios**: Explaining the "Zero Grad" step in training loops.

### Part 3: Neural Networks (`03_neural_networks.py`)
* **Building with `nn.Module`**: Creating custom classes for model architectures.
* **Activation & Loss functions**: Implementing ReLU, Softmax, and Cross-Entropy.
* **Training loops**: Standard patterns for forward passes and optimization.
* **Complete XOR problem**: A classic implementation to demonstrate non-linear boundaries.

### Part 4: Interview Problems (`04_interview_problems.py`)
* **Custom Dataset & DataLoader**: Implementing efficient data pipelines.
* **Batch Normalization**: Understanding internal covariate shift.
* **Gradient clipping**: Solving the exploding gradient problem.
* **Memory optimization**: Using `torch.inference_mode()` and clearing the cache.

### Part 5: Advanced Topics (`05_advanced_topics.py`)
* **Attention mechanisms**: Multi-Head Attention implementation.
* **Mixed precision training**: Using `torch.cuda.amp` for faster training with less memory.
* **Model quantization**: Reducing model size for edge deployment.
* **Dynamic computation graphs**: Explaining how PyTorch differs from static graph frameworks.

---

## Quick Start

### Option 1: Run Individual Parts
```bash
python 01_tensor_basics.py
python 02_autograd_gradients.py
python 03_neural_networks.py
python 04_interview_problems.py
python 05_advanced_topics.py
