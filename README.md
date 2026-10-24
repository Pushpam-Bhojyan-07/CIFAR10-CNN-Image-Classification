# CIFAR-10 Image Classification using CNN

## Overview
This project explores image classification using a Convolutional Neural Network (CNN) built with PyTorch. The model is designed to classify images from the CIFAR-10 dataset into one of ten object categories.

## Dataset
CIFAR-10 contains 60,000 color images of size 32 × 32 pixels across ten classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

The dataset contains 50,000 training images and 10,000 test images.

## Model
The CNN uses convolutional layers to extract image features, ReLU activation functions to introduce non-linearity, and max-pooling layers to reduce spatial dimensions. Fully connected layers produce class scores for the ten categories.

## Technologies
- Python
- PyTorch
- Torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

## How to Run
1. Clone this repository.
2. Install the required libraries:

   ```bash
   pip install torch torchvision numpy matplotlib jupyter
   ```

3. Launch JupyterLab:

   ```bash
   jupyter lab
   ```

4. Open `CNN_for_CIFAR10.ipynb` and execute the cells in order.

The notebook may download CIFAR-10 automatically if the dataset is not already available.

## Learning Outcomes
- Understanding CNN architecture
- Image preprocessing and normalization
- Model training and evaluation
- Multiclass image classification using PyTorch

## Author
**Pushpam Bhojyan**

GitHub: [Pushpam-Bhojyan-07](https://github.com/Pushpam-Bhojyan-07)