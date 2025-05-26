# The latest projects are in the Release v1.0
(I couldn't upload the heavy files)
## Lilit Azizyan
### CNN_YOLOv5
It is a friendly script that demonstrates how to run the pre-trained YOLOv5s model on a set of local images using PyTorch Hub and visualize the results directly in Google Colab.
### CNN_YOLOv8n
This script converts Pascal VOC 2012 annotations to YOLO format, splits the dataset into training and validation sets, creates the data.yaml file, and trains the YOLOv8n model for 30 epochs (due to the limited resources of using Colab's GPU). After training, it automatically backs up the best and last model weights to Google Drive.

In the release you will also see 2 videos one is 2103099_detected.mp4 and the other is 2103_detected.mp4. These videos showcase detection results using the trained YOLOv8n model. The differences between them are explained in the corresponding text cells within the Colab notebook.
## Dataset

[**Pascal-**](http://host.robots.ox.ac.uk/pascal/VOC/voc2012/)
The Pascal VOC 2012 dataset is a widely used benchmark for object detection, featuring 20 object categories (e.g., person, car, dog). It includes real-world images with XML annotations specifying bounding boxes and class labels.

The CNN_YOLOv8n project converts the Pascal VOC 2012 dataset to the YOLO annotation format, required for YOLO-based training and evaluation.




