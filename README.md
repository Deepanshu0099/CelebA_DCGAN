# CelebA_DCGAN
This assignment focuses on implementing a Deep Convolutional Generative Adversarial Network (DCGAN) using PyTorch. The goal is to train the model on the CelebA dataset and generate realistic-looking human face images.
We use the CelebA dataset, which contains over 200,000 celebrity face images. The dataset is downloaded and extracted using Kaggle API within the notebook.
Workflow:
Environment Setup: Import necessary libraries (PyTorch, torchvision, matplotlib, etc.)
Set up device (GPU if available)
Data Preprocessing:Load images from the CelebA dataset
Apply transformations: resizing, cropping, normalization
Model Architecture:
Generator: Takes a noise vector as input and learns to produce fake images
Discriminator: Classifies images as real or fake
Training:
Adversarial training of generator and discriminator
Loss functions: Binary Cross Entropy
