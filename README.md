# CUDA-transformations--GPU-vs-CPU

This project simulates image transformations using CUDA and compares the performance with CPU-based implementations.

## Project Overview

In this project, we implement and compare the performance of two image transformations: **Wave Transformation** and **Sobel Transformation**. The goal is to demonstrate the computational performance benefits of using CUDA for GPU-based processing compared to traditional CPU-based processing.

The project includes:
- A CPU implementation of the Wave transformation.
- A GPU implementation of the Wave transformation using CUDA.
- A CPU implementation of the Sobel transformation.
- A GPU implementation of the Sobel transformation using CUDA.
- Performance comparison of the two implementations, showcasing the speedup provided by CUDA.

## Features

- **Wave Transformation**: Applies a wave-like distortion to the image by modifying the pixel positions based on a sine function.
- **Sobel Transformation**: Uses the Sobel operator to perform edge detection by calculating the gradient of the image intensity at each pixel.
- **CUDA Optimization**: GPU implementations using CUDA to parallelize the transformations and improve performance.
- **CPU Benchmark**: CPU-based transformations for comparison.
- **Visualization**: Generates visual outputs of the transformations for both CPU and GPU implementations.
- **Performance Comparison**: Compares the execution times of the CPU and GPU implementations for both transformations.

## Installation

To run the code, you can either use a local Python environment or a cloud-based platform such as Google Colab.

### Prerequisites:

- **For CPU (Python)**: No special libraries are required other than standard ones like `numpy` and `matplotlib`.
- **For GPU (CUDA)**: You'll need **PyCUDA** installed to work with CUDA-enabled devices.

To install dependencies:

```bash
pip install pycuda numpy matplotlib
