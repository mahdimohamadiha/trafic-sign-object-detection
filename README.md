<img src="/yolov5.jpeg" alt="YOLOv5 logo" width="600px">

# What is YOLOv5?

On June 25th, 2020, the first official version of YOLOv5 was released by Ultralytics, a computer vision model used for detecting objects.
OLOv5 is a model in the You Only Look Once (YOLO) family of computer vision models. YOLOv5 comes in four main versions: small (s), medium (m), large (l), and extra large (x), each offering progressively higher accuracy rates. Each variant also takes a different amount of time to train.

<img src="/chart.png" alt="YOLOv5 chart" width="600px">

# How to Train YOLOv5

This project was done in the Google colab environment and it is recommended to run it there.
First, Runtime --> Change Runtime Type --> Hardware accelerator --> GPU.
This is to speed up the train.

Then upload the database and test folders and the dataset.yaml file to your Google Drive.

## Train steps

<ul>
  <li>Mount to Google Drive</li>
  <li>Import packages</li>
  <li>Clone YOLOv5</li>
  <li>Testing the annotations</li>
  <li>Partition the Dataset</li>
  <li>Add test pictures</li>
  <li>Data Config File</li>
  <li>Train with pretrained weights</li>
  <li>Train from scratch</li>
  <li>Inference</li>
</ul> 

## Methods of training

There are two ways to train. 

The first method uses a pretrained model and the second Train from scratch and use random weights.

The second method has lower accuracy due to not using the pretrained model.

