# StyleGAN Implementation and Hyperparameter Tuning

Author: Tarush Singh

## Table of Contents
- [Overview](#overview)
- [Task 1: Understand the Components of StyleGAN](#task-1-understand-the-components-of-stylegan)
- [Task 2: Implement Components of StyleGAN](#task-2-implement-components-of-stylegan)
- [Task 3: Compare PSO with Keras Tuner](#task-3-compare-pso-with-keras-tuner)

## Overview
This repository contains code for implementing and comparing components of StyleGAN, a variant of Generative Adversarial Networks (GANs). The code is organized into three main tasks.

## Task 1: Understand the Components of StyleGAN
StyleGAN introduces several components that distinguish it from traditional GANs. Some key components include:
- **Mapping Network**: A network used to transform a latent vector into an intermediate latent space for generating images.
- **Style Mixing**: Capability to combine different styles at different resolutions during the image generation process.
- **Adaptive Instance Normalization (AdaIN)**: A technique that modifies the mean and standard deviation of intermediate features to incorporate style information.
- **Noise Injection**: Controlled noise addition to the input of each layer for enhancing image variety.

## Task 2: Implement Components of StyleGAN
In this section, the code provides functions to implement components of StyleGAN, including:
- **Mapping Network**: A function to create a mapping network.
- **Generator**: A function to build the StyleGAN generator, incorporating components like AdaIN and noise injection.

The code then instantiates the generator and provides a summary of its structure.

## Task 3: Compare PSO with Keras Tuner
This section involves the comparison of two optimization methods, Particle Swarm Optimization (PSO) and Keras Tuner, for hyperparameter tuning. Key elements include:
- Using PSO to optimize hyperparameters for a neural network model.
- Utilizing Keras Tuner (RandomSearch) to search for the best hyperparameters for a Keras model.
- Measuring the time taken by each optimization method and evaluating the accuracy of the models.

### How to Run the Code
To run the code, follow these steps:
1. Clone this repository to your local machine.
2. Install the required dependencies, including TensorFlow and scikit-learn.
3. Execute the provided Python script for each task.

### Dependencies
- TensorFlow
- scikit-learn
- Keras Tuner
- pyswarm

### Acknowledgments
- This code was created by Tarush Singh as part of the "Intelligent Model Design Using AI Lab 9."

For more details, refer to the code files and comments in the repository.

