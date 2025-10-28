Fashion MNIST Classification
This project builds a deep learning model to classify fashion images from the Fashion-MNIST dataset using TensorFlow and Keras.
Dataset
Fashion-MNIST contains 60,000 training images and 10,000 test images of 28x28 grayscale pixels.  

Data Preparation

Load the dataset using keras.datasets.fashion_mnist.
Normalize pixel values by dividing by 255 to scale them between 0 and 1.

Model Architecture

The model is a simple sequential neural network:
- Flatten layer to convert 28x28 input into a 1D vector.
- Dense layer with 128 neurons and ReLU activation.
- Output Dense layer with 10 neurons and softmax activation for multi-class classification.
