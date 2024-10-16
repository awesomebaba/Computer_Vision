# Medicine Classification: Ayurvedic Plant Classification
## Project Overview

This project focuses on classifying various Ayurvedic medicinal plants using deep learning techniques. The model helps in the automatic identification of different medicinal plants from images, providing a tool for the healthcare and herbal medicine domain.

## Objective
The aim of this project is to develop a Convolutional Neural Network (CNN) that can classify images of different Ayurvedic medicinal plants based on their visual features. This can aid in faster and more accurate identification for medicinal purposes.

## Dataset
The dataset contains images of Ayurvedic plants classified into various categories. These images were divided into training, validation, and test sets.

#### Dataset Structure:
Training Set: Used to train the CNN model.

Validation Set: Used for tuning the model during training.

Test Set: Evaluated for the model's performance on unseen data.

## Model Architecture
The model employs a CNN architecture, which is well-suited for image classification tasks. The architecture includes:

Input Rescaling: Image rescaling to normalize pixel values.

Convolutional Layers: Multiple layers to extract key visual features.

MaxPooling Layers: Reduce dimensionality and prevent overfitting.

Batch Normalization: Improve training speed and stability.

Dropout Layers: Regularization to avoid overfitting.
Fully Connected Layers: Dense layers for final classification.

Output Layer: Uses Softmax for multi-class classification.

## Results
The trained model achieved significant accuracy in classifying Ayurvedic plants. It can be further optimized using techniques like data augmentation and hyperparameter tuning.



