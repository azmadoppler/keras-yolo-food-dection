# keras-yolo for Food Detection


[![license](https://img.shields.io/github/license/mashape/apistatus.svg)](LICENSE)

## Introduction

Forked from  qqwweee/keras-yolo3 to edit the training process and train with in order to detect the food

---

## How to use

 - Download the weight and stored in the /model_data/ and named it 'yolo_food.h5' Just run it using python yolo_video.py --image and input the image path
 - The result can be with the file called detection.png


---


## Dataset

A UECFood256 Dataset 

---

## TODO

- Try to convert to TF-Serving format to deploy with Flask 
- Upgrade the output to return the Bounding Box for all detection result
- Change from detect only one image to detect whole directory
---