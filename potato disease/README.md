# Potato Disease Classification
## Overview
This project uses a Convolutional Neural Network (CNN) to classify potato leaf images into three categories: Healthy, Early Blight, and Late Blight. It helps farmers and agricultural professionals quickly identify plant diseases, reducing crop losses and improving decision-making for treatment.

## Model Structure
Preprocessing: Images are resized, rescaled, and randomly flipped/rotated to improve training.

CNN Layers:
Multiple convolutional layers (Conv2D) with ReLU activation.

MaxPooling layers to reduce image size after each convolution.

Dense Layers:
A fully connected layer (Dense) with 64 units.
Output layer using softmax to classify the image into one of three categories.

### Input
Images with shape: (BATCH_SIZE, IMAGE_SIZE, IMAGE_SIZE, 3) (RGB images).
### Output
The model predicts one of three classes:
Healthy
Early Blight
Late Blight
### Training
The model is trained using the Adam optimizer and categorical cross-entropy loss.
