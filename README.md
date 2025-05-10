# SRGAN Model Implementation (PyTorch)

This repository contains a Jupyter Notebook (`SRGAN_model.ipynb`) that implements a Super-Resolution Generative Adversarial Network (SRGAN) model using PyTorch.

## Overview

This notebook demonstrates how to build, train, and evaluate an SRGAN model for enhancing the resolution of images. It includes the implementation of the generator and discriminator networks, a perceptual loss function using VGG16 features, and the training loop. The notebook utilizes the PyTorch framework.

## Contents

* `SRGAN_model.ipynb`: The Jupyter Notebook containing the SRGAN model implementation.
* `README.md`: This file, providing an overview of the project.

## Setup

To run this notebook, you will need:

* Python 3.x
* PyTorch
* Torchvision
* PIL (Pillow)
* (Optional) CUDA-enabled GPU for faster training

You can install the necessary libraries using pip:

```bash
pip install torch torchvision pillow