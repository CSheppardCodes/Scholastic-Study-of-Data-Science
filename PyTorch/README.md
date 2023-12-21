# PyTorch 1.2 Quickstart with Google Colab README

Author: Elvis Saravia

## Overview
This code tutorial provides a quick introduction to PyTorch 1.2, demonstrating fundamental concepts in training a deep learning model using Google Colab. The tutorial is inspired by the "Tensorflow 2.0 Quickstart for experts" notebook.

## Dependencies
To run the code, make sure to install the required dependencies using the following command:

!pip3 install torch==1.2.0+cu92 torchvision==0.4.0+cu92 -f https://download.pytorch.org/whl/torch_stable.html

## Importing Libraries
The code utilizes PyTorch and its associated modules for building and training the model:

- torch
- torch.nn as nn
- torch.nn.functional as F
- torchvision
- torchvision.transforms as transforms

## Importing the Data
The MNIST dataset is used for this tutorial, and the code demonstrates how to import, transform, and load the data efficiently using PyTorch's DataLoader.

## Exploring the Data
The code explores the dataset by visualizing random training images and checking the dimensions of a batch.

## The Model
The tutorial introduces a simple convolutional neural network (CNN) model using PyTorch.

## Training the Model
The code sets up a loss function, an optimizer, and a function to compute accuracy. It then trains the model over multiple epochs.

## Testing the Model
The tutorial includes code to evaluate the model on the testing dataset.

## Final Words
The tutorial concludes with a congratulatory message and suggests further explorations, such as extending the model with additional layers. It also provides references for additional learning resources.

---

### References
- Building RNNs is Fun with PyTorch and Google Colab
- CNN Basics with PyTorch by Sebastian Raschka
- Tensorflow 2.0 Quickstart for experts
