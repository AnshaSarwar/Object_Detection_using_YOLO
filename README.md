**Object Detection Using YOLOv8 with IoU Calculation**

This repository implements YOLOv8 for object detection, focusing on identifying and localizing objects in images. 
The model predicts bounding boxes for detected objects and evaluates their accuracy using Intersection over Union (IoU).

**Project Overview**

This project leverages the YOLOv8 (You Only Look Once) architecture for real-time object detection.
YOLOv8 is known for its speed and accuracy in detecting multiple objects within an image, assigning each object a class label and predicting its bounding box.

The model is designed to handle various object detection tasks, including recognizing objects in challenging scenarios such as occlusions and varying lighting conditions.

**Model Used**

YOLOv8: The latest version of the YOLO series, optimized for speed and performance, making it ideal for real-time applications.
It uses a single neural network for end-to-end object detection.

**IoU Calculation**
Intersection over Union (IoU) is used to measure the accuracy of predicted bounding boxes by comparing them with ground truth boxes. The IoU score is calculated as:

IoU = Area of Union / Area of Overlap
​
A higher IoU score indicates better alignment between the predicted and actual boxes, improving the precision of object detection.

**Dataset**

The dataset used for this project consists of images with labeled objects and their corresponding bounding boxes. 
The dataset is preprocessed for input into the YOLOv8 model.
