# EX 07-Convolutional Autoencoder for Image Denoising

## Overview

This project implements a Convolutional Autoencoder (CAE) for image denoising. The model learns to remove noise from corrupted images and reconstruct clean images by capturing important visual features through convolutional layers.

## Objectives

* Understand the concept of autoencoders.
* Develop a convolutional autoencoder for image denoising.
* Train the model using noisy and clean image pairs.
* Evaluate reconstruction quality and denoising performance.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* OpenCV

## Dataset

The model is trained using image datasets where noise is artificially added to clean images. The clean images serve as target outputs during training.

## Methodology

1. Load and preprocess image data.
2. Add noise to input images.
3. Build the Convolutional Autoencoder model.
4. Train the model using noisy-clean image pairs.
5. Reconstruct denoised images.
6. Evaluate model performance visually and quantitatively.

## Model Architecture

* Convolutional Layers
* Max Pooling Layers
* Bottleneck Layer
* UpSampling Layers
* Output Convolution Layer

## Results

The Convolutional Autoencoder effectively removes noise while preserving important image details. The reconstructed images show significant improvement compared to noisy inputs.

## Applications

* Medical Image Enhancement
* Image Restoration
* Surveillance Systems
* Satellite Image Processing
* Computer Vision Preprocessing

## Conclusion

This project demonstrates the effectiveness of Convolutional Autoencoders in image denoising tasks. By learning compact image representations, the model can reconstruct cleaner images and improve overall image quality.
