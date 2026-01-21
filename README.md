# Text-to-Image Latent Diffusion Model

This project implements a **Text-to-Image Latent Diffusion Model** using **PyTorch** and **CLIP**.

## Overview
- Images are encoded into a latent space using a Variational Autoencoder (VAE)
- Diffusion is performed in latent space for efficiency
- Text conditioning is done using pretrained CLIP text embeddings
- Images are generated from random noise guided by text prompts

## Tech Stack
- Python
- PyTorch
- Transformers (CLIP)
- Google Colab (GPU)

## Status
Educational implementation inspired by Stable Diffusion.
