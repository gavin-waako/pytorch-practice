# pytorch-practice

## PyTorch Deep Dive: Fundamentals of Tensor Operations
Welcome to the **PyTorch Mastery** repository! This project is a curated collection of foundational exercises designed to take you from a complete beginner to a confident practitioner. Whether you are learning for personal growth or preparing for a technical AI/ML interview, these resources provide the hands-on practice needed to master the framework.

## 📌 Overview
This repository serves as a **Complete PyTorch Curriculum**, moving from the absolute basics of tensor creation to more advanced manipulation and operations. Tensors are the fundamental building blocks of deep learning, and mastering them is essential for building and debugging complex neural networks.



## 🚀 Key Learning Modules
Based on the `pytorch_practice.py` script, this curriculum covers:

### 1. Tensor Creation & Initialization
* **Basic Structures**: Creating scalars, vectors, matrices, and multi-dimensional tensors using `torch.tensor()`.
* **Randomization**: Generating tensors with random values, including specific shapes used in computer vision, such as `[224, 224, 3]` for images.
* **Specialized Tensors**: Initializing data with `torch.zeros()`, `torch.ones()`, and creating ranges with `torch.arange()`.
* **Replication**: Using `torch.zeros_like()` to create tensors that mimic the shape of existing data.

### 2. Metadata & Inspection
* **Attributes**: Mastering the use of `.ndim`, `.shape`, and `.device` to inspect your data.
* **Datatypes**: Managing precision through `dtype` (e.g., `torch.float32` vs `torch.float16`) to optimize memory and performance.

### 3. Tensor Manipulations & Operations
* **Basic Arithmetic**: Element-wise addition, subtraction, multiplication, and division using both operators (e.g., `+`, `*`) and built-in functions like `torch.add()` or `torch.mul()`.
* **Advanced Operations**: Introduction to matrix multiplication, a core requirement for neural network layers.

## 🛠 Troubleshooting the "Big Three"
Deep learning bugs often stem from three specific areas. This guide provides the tools to identify and solve them:

* **Wrong Datatype**: Ensuring tensors are in the correct precision for the operation.
* **Wrong Shape**: Aligning dimensions for operations like matrix multiplication.
* **Wrong Device**: Verifying if tensors are on the same device (CPU vs. GPU/CUDA).

## 💻 Getting Started

**1. Clone the repository:**
```bash
git clone [https://github.com/gavin-waako/pytorch-practice.git](https://github.com/gavin-waako/pytorch-practice.git)
