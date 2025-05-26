# CNN projects
## Lilit Azizyan
This repository contains Convolutional Neural Network (CNN) projects developed using TensorFlow, Keras and Pytorch. 
All developments were done in **Google Colab**, making it easy to reproduce and experiment in a cloud-based environment.
# The latest projects are
### CNN_YOLOv5
It is a friendly script that demonstrates how to run the pre-trained YOLOv5s model on a set of local images using PyTorch Hub and visualize the results directly in Google Colab.
### CNN_HW3_FINAL
This script converts Pascal VOC 2012 annotations to YOLO format, splits the dataset into training and validation sets, creates the data.yaml file, and trains the YOLOv8n model for 30 epochs (due to the limited resources of using Colab's GPU). After training, it automatically backs up the best and last model weights to Google Drive.

In the repository you will also see 2 videos one is 2103099_detected.mp4 and the other is 2103_detected.mp4. These videos showcase detection results using the trained YOLOv8n model. The differences between them are explained in the corresponding text cells within the Colab notebook.
## Datasets that were used 

[**CIFAR-10** ](https://www.cs.toronto.edu/~kriz/cifar.html)
The dataset contains 60,000 32x32 color images in 10 classes, with 6,000 images per class. It is automatically downloaded via Keras:
```python
from tensorflow.keras.datasets import cifar10
(x_train, y_train), (x_test, y_test) = cifar10.load_data()
```
[**Pascal-**](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/)
The Pascal VOC 2012 dataset is a widely used benchmark for object detection, featuring 20 object categories (e.g., person, car, dog). It includes real-world images with XML annotations specifying bounding boxes and class labels.

In this project, the dataset is converted to YOLO format:
<class_id> <x_center> <y_center> <width> <height> (all normalized).
This format is used for training and evaluation with YOLO-based models.


## Features

- Customizable CNN architecture
- Training and evaluation scripts
- Accuracy & loss visualization
- Model saving


