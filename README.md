# DDPM with Hugging Face

## Overview
This repository contains a Colab Notebook implementing **Denoising Diffusion Probabilistic Models (DDPM)** using **Hugging Face** libraries. DDPM is a generative model used for image synthesis, leveraging a diffusion process to generate high-quality images.

## Features
- Implementation of DDPM using Hugging Face
- Training and inference for image generation
- Step-by-step explanation of the diffusion process
- Integration with PyTorch and Hugging Face Diffusers
- Custom dataset loading and preprocessing
- Visualization of diffusion steps

## Technologies Used
- **Python 3.7+**: Programming language for implementation
- **PyTorch**: Deep learning framework for model training and inference
- **Hugging Face Transformers**: Provides pre-trained models and utilities
- **Diffusers**: Hugging Face library for diffusion models
- **Matplotlib & Seaborn**: Visualization of training and results
- **Datasets**: Hugging Face dataset library for loading and processing data

## Process Overview
1. **Data Preprocessing**:
   - Load dataset using Hugging Face `datasets` library
   - Normalize and resize images for training
   - Convert images to tensor format

2. **Model Architecture**:
   - Utilize the DDPM framework with a U-Net architecture
   - Implement noise scheduling and diffusion steps
   - Use PyTorch and Diffusers for model components

3. **Inference & Generation**:
   - Sample noise and reverse the diffusion process
   - Generate high-quality images step by step
   - Visualize the final results and intermediate steps




