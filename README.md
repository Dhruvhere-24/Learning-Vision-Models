# Vision Models Learning

A collection of computer vision experiments focused on understanding how deep learning models work in practice.  
This project explores neural network architectures and their applications in image processing and generation.

The goal is to build practical intuition by implementing and experimenting with different vision models.

---

## Project Overview

This repository focuses on learning and experimenting with core computer vision techniques such as:

- Understanding the difference between ANN and CNN
- Image reconstruction and enhancement
- Image generation using GANs
- Image segmentation techniques

Each module demonstrates a different concept in deep learning for vision tasks.

---

## Implemented Modules

### 1. ANN vs CNN

This module explores the architectural differences between Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN).

Topics covered:

- Why CNNs work better for images
- Convolution operations
- Feature extraction
- Spatial information preservation

The goal is to understand **how CNN processes images differently from standard neural networks**.

---

### 2. Image Colorizer (Autoencoder)

A deep learning model that converts grayscale images into color images using an **autoencoder architecture**.

Workflow:-
Grayscale Image
↓
Encoder
↓
Latent Representation
↓
Decoder
↓
Colored Image


This model learns to reconstruct color information from grayscale inputs.

---

### 3. Image Upscaler

A neural network designed to improve image resolution.

Capabilities:

- Increase image resolution
- Restore visual details
- Improve image clarity

This module explores how deep learning models can reconstruct higher-resolution images from low-resolution inputs.

---

### 4. Anime Image Generator (GAN)

A Generative Adversarial Network (GAN) used to generate anime-style images.

Architecture:
Noise Vector
↓
Generator
↓
Generated Image
↓
Discriminator
↓
Real / Fake Classification


The generator learns to create realistic images while the discriminator learns to distinguish real images from generated ones.

---

### 5. Image Segmentation (Under Development)

This module aims to implement image segmentation models that identify and separate objects within images.

Planned features:

- Pixel-level classification
- Object boundary detection
- Semantic segmentation

Currently under development.

---

## Technologies Used

- Python
- PyTorch / TensorFlow
- NumPy
- OpenCV
- Matplotlib

---

## Project Goal

The primary goal of this project is to **develop a deeper understanding of computer vision models** by experimenting with different architectures and tasks such as reconstruction, enhancement, generation, and segmentation.

---

## Status

Project in active development.  
More vision models and experiments will be added.
