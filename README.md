# Semi supervised models for clutter and multiple instances
<br>
Author: Saurabh Kumar Jain, Shovakar Bhattacharjee

## Introduction 
In our project, we proposed a new object detection dataset with 19 categories with a vision to boost the performance of the task
of object detection for cluttered objects. We also demonstrate the efficacy of the one-stage, two-stage, and semi-supervised object detection models both quantitatively and qualitatively on our proposed cluttered dataset.

## Dataset
The proposed cluttered dataset can be downloaded from [here](https://drive.google.com/drive/folders/1y0z0FfLLCatNrM4dgZJISOZ9noUQcXZ3?usp=drive_link)

## Description of files
* TRAIN_YOLOv5.ipynb: For reproducing one-stage (i.e., YOLO-V5) object detector results.
* faster_rcnn_Detectron2.ipnyb: For reproducing two-stage (i.e., Faster R-CNN) object detector results.
* SoftTeacher: Use readme.txt of original [repo](https://github.com/microsoft/SoftTeacher) for reproducing semi-supervised model results using our dataset. 
