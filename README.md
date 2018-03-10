# Deep Learning Practice

This repository contains IPython notebooks and some python codes that I used to practice deep learning and neural network.

* Read this in other language: [한국어](README.ko.md)

## Environment
- Python3.6
    - Check the requirement.txt
    - Install requirement packages:
        - cpu only
        ```
        $ pip install -r requirements.txt 
        ```    
        - cpu and gpu
        ```
        $ pip install -r requirements_gpu.txt
        ```
        
    - Recommended using virtualenv to install and run.
    - It includes Keras deep learning package with TensorFlow backend.
    - Tensorflow with gpu can be install by replacing requirement.txt from tensorflow to tensorflow-gpu.

## Table of Contents

### Supervised Learning
0. Neural Network Theory
    1. Neuron and Perceptron
    2. Activation Function
    3. Softmax
    4. __Gradient Descent Method__
    5. __Back Propagation__
        1. __Stochastic Gradient Descent__
        2. __Adam__
1. Regression
    1. Simple Linear Regression
        1. Gradient Descent Implementation
    2. Least Square Approximation
    3. Single Hidden-layer Network Regression Practice
    4. Boston Housing Regression
2. Image Classifier
    1. Basic Classifier Practice
    2. MNIST Classifier - Single Dense Layer
        1. Single Dense Layer w/ Visualization
    3. MNIST Classifier- Single Hidden Layer
    4. Mult-layered Neural Network
    5. Convolution Filter
        1. Pooling Layer
        2. MNIST Classifier - Convolution Network
        3. CIFAR10 Classifier - Convolution Network
        4. fashion_MINST - Convolution Network
    6. MNIST - VGG 16, VGG 19 Network
    7. CIFAR10 - ResNet
3. Text and Sequence
    1. IMDB Text Classifier - CNN
    2. IMDB Sentiment Classifier - LSTM
4. Time Series
    1. Binary Adder - RNN
    2. Airline - RNN Time Series Prediction
    3. Power Consumption - LSTM Prediction
    4. Numeric Adder - LSTM

### Unsupervised Learning
5. Autoencoder
    1. MNIST - Autoencoder Fully Connected
    2. MNIST - Autoencoder CNN
    3. CIFAR10 - UNET Color Restoration
6. Generative Adversarial Networks
    1. Probabilistic Distribution - Fully Connected GAN
    2. MNIST - CNN GAN

* Italic means the contents is not uploaded yet or not fully written.

## Miscellaneous Notes
- Tips
    - Keras
        - Save/Load Model
        - Preprocessing Image (Augmented Image Generator)
    - TensorFlow
        - Basic Grammer
        - Save, Load
        - Tensorboard

## References
Some data was brought from https://github.com/Jpub/TensorflowDeeplearning jupyter_tfbook


