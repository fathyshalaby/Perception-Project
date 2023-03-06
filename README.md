# YOLOv8 Traffic Object Detection Readme

This repository contains code to train a YOLOv8 model on the COCO dataset for the task of road traffic object detection and classification on a video clip. The aim is to identify and track objects such as cars, trucks, motorcycles, and buses in the video clip.

Dataset

The COCO dataset was used for training the model. The dataset is widely used for object detection tasks and contains annotations for a wide variety of objects, including those typically found in road traffic scenarios. The dataset can be downloaded from the following link: https://cocodataset.org/#download.

Method

The You Only Look Once version 8 (YOLOv8) object detection algorithm was used for this project. This algorithm is known for its high accuracy and fast processing speed, making it ideal for real-time object detection tasks. The YOLOv8 algorithm is based on a convolutional neural network architecture and uses a single neural network to predict bounding boxes and class probabilities directly from full images.

Libraries Used

The supervisely library was used to process the data and generate the required annotations for the COCO dataset. The opencv-python library was used for reading and processing the video clip. The tensorflow and keras libraries were used to train and evaluate the YOLOv8 model.

Files

The following files are included in this repository:

train.py: This file contains the code to train the YOLOv8 model on the COCO dataset.
inference.py: This file contains the code to perform object detection and classification on a video clip using the trained YOLOv8 model.
requirements.txt: This file contains the required libraries and their versions.
Usage

To use this code, follow the steps below:

Download the COCO dataset from the link provided above.
Use the supervisely library to process the data and generate the required annotations for the COCO dataset.
Update the paths to the COCO dataset and annotations in the train.py file.
Run the train.py file to train the YOLOv8 model.
Once the model is trained, update the path to the video clip in the inference.py file.
Run the inference.py file to perform object detection and classification on the video clip.
Conclusion

In this project, we used the YOLOv8 algorithm and the COCO dataset to train a model for road traffic object detection and classification on a video clip. The trained model can be used for real-world scenarios such as traffic monitoring and surveillance.
