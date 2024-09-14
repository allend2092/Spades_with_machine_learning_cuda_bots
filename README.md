# Spades with Machine Learning CUDA Bots

## Introduction

This project is a text-based implementation of the classic card game **Spades**, featuring bots that learn and improve their gameplay using machine learning techniques. The bots are powered by neural networks implemented with **PyTorch** and leverage **CUDA** for GPU acceleration. The program was created as a learning exercise to understand neural networks and machine learning in a practical context.

## Features

- **Text-Based Spades Game**: Play the game of Spades in a console environment.
- **Machine Learning Bots**: Bots use neural networks to make bidding decisions and play cards.
- **Self-Learning**: Bots learn from their gameplay experiences and improve over time.
- **GPU Acceleration**: Utilizes CUDA and PyTorch to run neural networks on the GPU for faster computation.
- **Customizable**: Adjust the number of human players and bots.
- **Model Persistence**: Bots save their neural network models after training, allowing them to retain learned behaviors between sessions.

## Requirements

- **Python 3.x**: The program is written in Python and requires Python 3.x.
- **PyTorch**: Used for implementing and training neural networks.
- **CUDA-Compatible GPU**: To take advantage of GPU acceleration, a CUDA-compatible GPU with sufficient VRAM is recommended. The program has been tested on an **NVIDIA GeForce RTX 3080 (10GB VRAM)**.
- **Keyboard Module**: Used for detecting key presses (e.g., 'q' for graceful exit). Install with `pip install keyboard`.

### Recommended GPU Specifications

- **NVIDIA GeForce RTX 3080 (10GB VRAM)**
  - **CUDA Cores**: 8704
  - **Boost Clock**: 1.71 GHz
  - **Memory Interface Width**: 320-bit
  - **Memory Bandwidth**: 760.3 GB/s
  - **VRAM**: 10 GB GDDR6X

The program's neural networks are resource-intensive and require a GPU with at least **10GB of VRAM** for optimal performance.

## How to Run

1. **Clone the Repository**:
   ```bash 
   git clone https://github.com/allend2092/Spades_with_machine_learning_cuda_bots.git
   ```

2. Install Dependencies:

``` pip install torch keyboard ```

Ensure that PyTorch is installed with CUDA support. Visit PyTorch's official website for installation instructions specific to your system.

Run the Program:

python spades_with_pytorch_ML.py

Gameplay:
The game is set up with 0 human players by default. To play as a human, adjust the num_human_players variable in the main() function.
Press 'q' at any time to gracefully exit the game. The bots will save their trained models before exiting.

Purpose:
This project was created to explore and understand neural networks and machine learning through a practical application. Implementing machine learning in a familiar game context like Spades provides an engaging way to learn about AI agents, training processes, and the challenges involved in developing intelligent systems.

Previous Versions:
This code is an evolution of a previous attempt at implementing Spades with machine learning. The initial version can be found here:

Previous Attempt - Version 1.0
https://github.com/allend2092/Spades_ML/tree/main/attempt_two/version_1_0

The current version improves upon the original by refining the neural network architectures, optimizing performance for GPUs, and enhancing the bots' learning capabilities.

License:
This project is licensed under the terms of the MIT License.
