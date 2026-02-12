# Convolutional Variational Autoencoder (VAE) on Binarized MNIST
## Overview

This repository contains a beginner-friendly implementation of a **Convolutional Variational Autoencoder (VAE)** in **PyTorch**, trained on the **binarized MNIST** dataset.

Main goals of this project:

- Learn how to build a probabilistic generative model
- Understand the encoder → latent distribution → decoder flow
- See the balance between reconstruction quality and latent space regularization
- Generate new handwritten digits by sampling from the learned latent space

Built as a learning project after completing an introductory deep learning course.

## Key Features

- Convolutional layers in both encoder and decoder
- Binarized input (pixels strictly 0 or 1)
- Reparameterization trick for differentiable sampling
- Standard VAE objective: BCE reconstruction + KL divergence
- Default latent dimension = 2 (easy to visualize in 2D later)
- Clear separation of encoder/decoder forward passes
- Training progress shows separate reconstruction and KL losses

## Example Training Output (10 epochs)
