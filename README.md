# Multiclass Object detection in Images

Brief description of what the project does and who it's for.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Report](#report)
- [Code Files](#code-files)

## Introduction
The objective of this project is to detect 5 different classes in a given image. These
classes are - car, truck, pedestrian, traffic light and bicyclist. The task of object detection will be
done using 2 different machine learning algorithms; SVM and YOLO algorithm. 
The primary objective is to compare the inference times of YOLO and SVM for multiclass object detection.

## Dataset
The dataset that was used for this project was the ‘Self-driving cars’ dataset on [Kaggle](https://www.kaggle.com/datasets/alincijov/self-driving-cars?resource=download). 
This dataset contains 22,241 images, divided into train and test splits. The images contain
multiple objects from the given 5 classes.

## Report
Report.pdf contains a detailed report on the project and the methodologies implemented.

## Code Files
List and description of important code files in the project.
- `SVM.ipynb` - contains the SVM implementation for object detection.
- `YOLOv5.ipynb` - contains the YOLO implementation for object detection
