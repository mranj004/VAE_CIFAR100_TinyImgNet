Variational Autoencoder Representation Study: CIFAR-100 vs. Tiny ImageNet Overview

Hi, thanks for checking out this project.

This project investigates how dataset scale and visual complexity affect the quality of representations learned by a variational autoencoder (VAE). A convolutional VAE was trained on CIFAR-100 and Tiny ImageNet using a shared experimental framework to compare reconstruction performance, latent-space structure, and downstream feature usefulness.

The project uses a convolutional encoder-decoder architecture with a Gaussian latent space. Training optimizes a reconstruction objective together with KL-divergence regularization, encouraging the model to learn compact latent representations that preserve meaningful image information.

Project Goals: 
Builds a reusable PyTorch VAE pipeline for CIFAR-100 and Tiny ImageNet.
Compares learned latent representations across datasets with different scale and complexity.
Tracks reconstruction and KL-divergence losses during training.
Saves best validation checkpoints and exports training metrics.
Evaluates latent representations using a linear-probe classifier.

Tools used:
Python, PyTorch, torchvision, Hugging Face Datasets, scikit-learn, YAML, pandas, Matplotlib

