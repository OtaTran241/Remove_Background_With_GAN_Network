# Background Removal using GAN with PyTorch

This project implements a Generative Adversarial Network (GAN) to perform background removal from images. The model is trained to generate images without backgrounds given images with backgrounds, effectively learning the task of background subtraction.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
  - [Generator (GModel)](#generator-gmodel)
  - [Discriminator (DModel)](#discriminator-dmodel)
- [Training](#training)
- [Inference](#inference)
- [Dependencies](#dependencies)
- [Usage](#usage)
  - [Training the Model](#training-the-model)
  - [Generating Images](#generating-images)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project leverages a GAN consisting of a generator (`GModel`) and a discriminator (`DModel`) to remove backgrounds from images. The generator learns to produce images without backgrounds, while the discriminator differentiates between real images (with no background) and generated images.

## Dataset
The dataset used in this project consists of paired images:
- **Images with backgrounds**: Input images that contain the background.
- **Images without backgrounds**: Target images that do not have the background.

Dataset link [here](https://www.kaggle.com/datasets/cooperbuch/images-with-no-background-for-background-removal)
