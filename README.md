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
1. Create a virtual environment (Using name cvhw2 for instance) using conda in python 3.10.  
```conda create -n cvhw2 python=3.10 -y```
2. Activate the conda environment.
```conda activate cvhw2```
3. Install the requirements using pip  
```pip install -r requirements.txt```

## Performance Snapshot
The overall performance is 0.33, and 0.69 for the two tasks :(  
<img width="1152" alt="截圖 2025-04-16 晚上8 45 01" src="https://github.com/user-attachments/assets/5eea022c-d087-4d20-902e-0a90f59f8984" />
