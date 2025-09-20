MNIST Autoencoder Project
Overview

This project implements a basic autoencoder using the MNIST dataset of handwritten digits. An autoencoder is a type of neural network designed to compress input data into a smaller latent representation and then reconstruct the original data from that compressed representation.

The project demonstrates:

Building an encoder-decoder network

Training on the MNIST dataset

Evaluating reconstruction performance

Plotting training/validation loss curves

Comparing original and reconstructed images

Dataset

Dataset: MNIST handwritten digits

Number of samples: 60,000 training, 10,000 testing

Image size: 28×28 pixels, grayscale

Model Architecture
Encoder

Input layer: 784 (28×28 flattened)

Dense layer: 128 neurons, ReLU activation

Dense layer: 64 neurons, ReLU activation

Latent layer: 32 neurons, ReLU activation

Decoder

Dense layer: 64 neurons, ReLU activation

Dense layer: 128 neurons, ReLU activation

Output layer: 784 neurons, sigmoid activation
