# Dental Image Denoising using PyTorch (Autoencoder Approach)

This repository contains a PyTorch implementation of a **Denoising Autoencoder (DAE)** to remove noise from **dental X-ray images**. The model is trained in an **unsupervised** manner, meaning it does not require paired clean/noisy images.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
- [Contact](#contact)

## Overview
The Denoising Autoencoder (DAE) is a neural network-based approach designed to remove noise from dental X-ray images. It is built on a **U-Net architecture**, which captures fine details and reconstructs clean images from noisy inputs.

This implementation processes **120 dental images**, extracting useful features while eliminating unwanted noise. The model can be applied to improve diagnostic accuracy in dental imaging.

## Dataset
The dataset consists of **120 noisy dental X-ray images**, stored in a directory structure as follows:



### Dataset Details
- Format: JPG
- Image Type: Dental radiographs (X-rays)
- Resolution: Varies based on dataset
- Preprocessing: Images are normalized before training

## Methodology
### Key Steps
1. **Data Loading:** Load noisy dental images and apply preprocessing.
2. **Model Definition:** Implement a U-Net-based autoencoder.
3. **Training:** Train the model using a Mean Squared Error (MSE) loss function.
4. **Evaluation:** Test the model on noisy images and visualize denoised outputs.

### Key Components
- **U-Net Autoencoder:** Encoder extracts features; decoder reconstructs images.
- **Loss Function:** Uses MSE loss by default, with an option for Structural Similarity Index (SSIM) loss.
- **Training Strategy:** Optimized using Adam optimizer with a learning rate scheduler.

## Dependencies
To run this project, install the required Python libraries:

```bash
pip install torch torchvision numpy opencv-python

git clone https:https://github.com/AyobamiMichael/Dental_Medical_ImagesDenoising.git
cd Dental_Medical_ImagesDenoising


Results
   The model produces the following outputs:
   Denoised Dental X-rays: Each input image is processed and saved in the output directory.



## Contact
  For questions or feedback

Ayobami Opefeyijimi
Email: ayobamiwealth@gmail.com

