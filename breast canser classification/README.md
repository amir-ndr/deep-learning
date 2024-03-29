# Breast Cancer Classification

This Python project aims to classify breast cancer images into two categories: healthy and cancerous. It utilizes a convolutional neural network (CNN) to make predictions based on image patches.

## Table of Contents
1. [Problem](#1)
2. [Preparing the Dataset](#2)
3. [Dataset Information](#3)
4. [Examples](#4)
5. [Data Generators](#5)
6. [Model](#6)
    - [Designing the Model](#6.1)
    - [Compiling the Model](#6.2)
    - [Callbacks](#6.3)
    - [Training the Model](#6.4)
7. [Evaluation](#7)

## Problem <a name="1"></a>

Breast cancer is a common form of cancer, and early detection is crucial. This project tackles the task of identifying cancerous regions in breast tissue images, which is a crucial step in cancer diagnosis.

## Preparing the Dataset <a name="2"></a>

The dataset consists of breast tissue images, categorized into healthy and cancerous classes. The images are preprocessed and organized for training and evaluation.

## Dataset Information <a name="3"></a>

The dataset contains two classes: healthy and cancerous. It's balanced and suitable for training a machine learning model. 

## Examples <a name="4"></a>

Sample images from the dataset are displayed to provide insights into the data.

## Data Generators <a name="5"></a>

Data generators are created to efficiently load and preprocess images for model training. This helps manage large datasets.

## Model <a name="6"></a>

### Designing the Model <a name="6.1"></a>

A CNN architecture is designed to classify breast tissue images. It includes convolutional layers, batch normalization, dropout, and fully connected layers.

### Compiling the Model <a name="6.2"></a>

The model is compiled with the Adam optimizer and binary cross-entropy loss function.

### Callbacks <a name="6.3"></a>

Callbacks like model checkpointing and early stopping are used to monitor and save the best model during training.

### Training the Model <a name="6.4"></a>

The model is trained on the dataset for multiple epochs to achieve optimal performance.

## Evaluation <a name="7"></a>

The model's performance is evaluated on a validation dataset, and predictions are generated. The project also provides insights into the model's accuracy and visualizations of its predictions. So after creating the datasets and preprocessing the images, we create a CNN model and compile it with adam optimizer, then fitted it during 27 epochs with batch_size=128. at the end we got 90 percentage accuracy on the validation set. you can also see the other evaluation in the jupyter notebook.

---
