# NYCU-Visual-Recognition-Using-Deep-Learning-2025-HW2
StudentID: 110550085
Name: 房天越

## Introduction
In this homework, we aim to apply Faster R-CNN to do Digit Recognition.
I use ResNet‑50 with FPN v2 as my backbone, and use data augmentation to improve the performance.
For the evaluation part, two stages are applied.
The first is to generate the bounding box and the class for each picture, the output file would be in COCO format.
The second is to generate the predicted numbers according to the result of the first stage.

## How to install
1. Create a virtual environment using conda in python 3.10.
```conda create -n vrdlhw2 python=3.10 -y```
2. Install the requirements using pip
```pip install -r requirements.txt```

## Performance Snapshot
