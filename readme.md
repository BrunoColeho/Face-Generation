# GAN Project: CelebA Face Generation

This project implements a Generative Adversarial Network (GAN) using PyTorch to generate realistic faces. The GAN is trained on the CelebA dataset to learn how to generate new face images.

## Project Structure

The project is organized as follows:

- **`Generator` and `Critic` Classes:** Define the architectures of the generator and discriminator networks.

- **GAN Training:** The training loop is implemented, including the training phase for both the discriminator and generator.

- **`Dataset` Class:** A custom class to load and process the CelebA dataset.

- **Checkpoints:** Functions to save and load model checkpoints during training.

- **Results Visualization:** Display of generated images at different training stages and visualization of loss curves.

- **Generating New Faces and Interpolation:** Generation of new faces after training and smooth interpolation between two images in latent space.

## Prerequisites

Before running the code, make sure to have the necessary libraries installed. 


## Dataset

This project utilizes the CelebA dataset, which includes images of celebrity faces.

### Dataset Download

The CelebA dataset is automatically downloaded during the execution of the code. Ensure that you have sufficient disk space for the download and extraction.

## Weights and Biases (wandb) Setup

The project uses the wandb library for result visualization during training. Follow the instructions below to set up wandb:

1. Create an account on Weights and Biases.
2. Install the wandb package: `pip install wandb`.
3. Replace 'INSERT YOUR API KEY!!!' in the line `wandb.login(key='INSERT YOUR API KEY!!!')` with your wandb API key.

## GAN Training

To train the GAN, execute the `GAN_Face_Generator` script. Training will proceed over multiple epochs, and generated images will be displayed during the process.

## Results

At the end of training, the project will showcase generated images, loss curves, and a smooth interpolation between two images in latent space.

## Udemy Course by Professor Javier Ideami

This project was created based on the course by Professor Javier Ideami, available on Udemy. The course provides an in-depth understanding of Generative Adversarial Networks (GANs) and their application in image generation.
