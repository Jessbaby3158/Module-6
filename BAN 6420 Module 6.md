Fashion MNIST Classification using CNN

Introduction
This project uses a Convolutional Neural Network (CNN) built with Keras to classify images from the Fashion MNIST dataset. The model is trained with six layers to predict 10 different clothing categories.

 Requirements
- Python 3.x
- TensorFlow (Keras backend)
- Numpy
- Matplotlib


Model Architecture
The CNN consists of the following layers:

Conv2D (32 filters, 3x3 kernel, ReLU activation)
MaxPooling2D (2x2 pool size)
Conv2D (64 filters, 3x3 kernel, ReLU activation)
MaxPooling2D (2x2 pool size)
Conv2D (64 filters, 3x3 kernel, ReLU activation)
Flatten layer
Dense (64 units, ReLU activation)
Dense (10 units, softmax activation)

Predictions
After training, the model is used to predict the labels for two test images from the Fashion MNIST dataset.
