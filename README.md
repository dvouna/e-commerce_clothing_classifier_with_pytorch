# Fashion Image Classifier using PyTorch

[![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch Version](https://img.shields.io/badge/pytorch-1.10+-orange.svg)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This project leverages the power of PyTorch to build a robust image classification model tailored for fashion items. 

### Introduction & Purpose 
Artificial Intelligence is transforming the ecommerce industry helping businesses enhance customer experiences, streamline operations and improve revenue generation. 

The project leverages the power of PyTorch, a deep learning library, to build a robust image classification moel for an online retail company. The model can be used tor categorizing new product listings, making it easier for customers to find what they are looking for. It can also be used for quickly sorting out items and for managin inventory.  

### Installation & Setup 
* **Python 3.8 or higher:** You can download it from [https://www.python.org/downloads/](https://www.python.org/downloads/).
* **PyTorch (>= 1.10):** Install PyTorch following the instructions on the official website: [https://pytorch.org/get-started/locally/](https://pytorch.org/get-started/locally/). Ensure you select the appropriate CUDA configuration if you have a GPU.
* **torchvision:** This package provides popular datasets, model architectures, and image transformations for PyTorch. Install it alongside PyTorch.

### Dataset 
The project uses the (FashionMNIST) dataset, containing images of about 70,000 clothing items, which makes it easier to ensure consistency across experiements. The dataset is imported from torch vision datasets.

### Model Architecture 
The dataset is split into train and test datasets and loaded into dataloader classes.
The model uses Python's Object Oriented Programming concept to build a comprehensive CNN model. 
A trining function for executing the model is defined. The function executes the model, calculates loss and updates the model parameters.

### Performance Metrics
The model is then used on the test dataset and metrics computed depending on the outputs of the test data. 
