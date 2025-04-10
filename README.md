# CNN projects
Convolutional Neural Networks

This repository contains a Convolutional Neural Network (CNN) project developed using TensorFlow and Keras. The core model is based on the ResNet architecture and is trained on the CIFAR10 dataset for image classification tasks.

All development was done in **Google Colab**, making it easy to reproduce and experiment in a cloud-based environment.

## Dataset

[**CIFAR-10** ](https://www.cs.toronto.edu/~kriz/cifar.html)
The dataset contains 60,000 32x32 color images in 10 classes, with 6,000 images per class. It is automatically downloaded via Keras:

```python
from tensorflow.keras.datasets import cifar10
(x_train, y_train), (x_test, y_test) = cifar10.load_data()
```

## Features

- Customizable CNN architecture
- Training and evaluation scripts
- Accuracy & loss visualization
- Model saving


