# Colorectal Cancer Detection using ResNet18


This project implements a deep learning solution for colorectal cancer detection using the ResNet18 architecture. The system is designed to classify histological images into three categories: MUS (Mucosa), NORM (Normal), and STR (Stroma).


## Project Overview


The project uses PyTorch to implement a ResNet18-based model for automated classification of colorectal cancer histological images. The system achieves high accuracy in distinguishing between different tissue types commonly analyzed in colorectal cancer diagnosis.


## Key Features


- Implementation of ResNet18 architecture for image classification

- Data preprocessing and augmentation pipeline

- Training with GPU acceleration support

- Cross-validation and performance metrics

- Model testing and evaluation

- Support for TIF image format


## Requirements


- Python 3.x

- PyTorch

- torchvision

- numpy

- scikit-learn

- matplotlib

- PIL (Python Imaging Library)

- Google Colab (for GPU acceleration)


## Project Structure


- `COMP432_Task1.ipynb`: Main training notebook containing model implementation and training code

- `TesterCode.ipynb`: Testing notebook for evaluating model performance

- Model achieves high accuracy on test data with comprehensive evaluation metrics


## Usage


1. Mount Google Drive in Google Colab

2. Load the dataset containing MUS, NORM, and STR images

3. Run the training notebook to train the model

4. Use the testing notebook to evaluate model performance


## Model Performance


The model demonstrates excellent performance metrics:

- High classification accuracy across all three classes

- Robust performance on validation and test sets

- Detailed performance metrics available in classification reports


## Dataset


The project uses a dataset of histological images in three categories:

- MUS (Mucosa)

- NORM (Normal tissue)

- STR (Stroma)


Images should be in TIF format and organized in corresponding directories.
