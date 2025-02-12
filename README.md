Handwritten Digit Recognition on MNIST Dataset

Overview

This project implements a Convolutional Neural Network (CNN) to recognize handwritten digits using the MNIST dataset. The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0-9), each of size 28x28 pixels.

Features

Data preprocessing (normalization and reshaping)

CNN-based deep learning model using TensorFlow/Keras

Model training and evaluation

Performance metrics such as accuracy, confusion matrix, and classification report

Visualization of predictions and misclassifications

Dataset

The MNIST dataset is available through TensorFlow/Keras and consists of:

60,000 training images

10,000 test images

Model Architecture

The CNN model consists of:

Convolutional Layers – Feature extraction from input images

Pooling Layers – Reducing spatial dimensions while retaining essential features

Fully Connected Layers – Final classification into digits 0-9

Softmax Activation – Outputs probability distribution over classes

Evaluation

After training, evaluate the model using:

Accuracy on test data

Confusion matrix for detailed performance analysis

Visualizing correct and incorrect predictions
