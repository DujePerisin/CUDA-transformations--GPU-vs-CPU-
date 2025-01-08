# Wave Propagation Simulation: CUDA vs CPU Comparison

This project simulates 1D wave propagation using the finite difference method. It compares the computational performance of the CPU-based and GPU-based (CUDA) approaches. The goal is to demonstrate how CUDA can significantly accelerate the computation of large-scale simulations compared to traditional CPU implementations.

## Project Overview

In this project, we simulate a wave traveling through a 1D medium (like a stretched string) using the **wave equation**. The wave is initialized with a disturbance in the middle, and its propagation is computed over multiple time steps. We use the **finite difference method (FDM)** to approximate the solution to the wave equation.

The project includes:
- A CPU implementation of the wave propagation.
- A GPU implementation of the wave propagation using CUDA.
- Performance comparison of the two implementations, showcasing the speedup provided by CUDA.

## Features

- **Wave Propagation Simulation**: Implements the 1D wave equation using the finite difference method.
- **CUDA Optimization**: GPU implementation using CUDA to parallelize the simulation and improve performance.
- **CPU Benchmark**: CPU-based simulation for comparison.
- **Visualization**: Generates an animation of the wave propagation and saves it as an MP4 video.
- **Performance Comparison**: Compares the execution times of the CPU and GPU implementations.

## Installation

To run the code, you can either use a local Python environment or a cloud-based platform such as Google Colab.

### Prerequisites:
- **For CPU (Python)**: No special libraries are required other than standard ones like `numpy` and `matplotlib`.
- **For GPU (CUDA)**: You'll need **PyCUDA** installed to work with CUDA-enabled devices.

To install dependencies:

```bash
pip install pycuda numpy matplotlib
