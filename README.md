# RSNA Pneumonia Detection Challenge
## Overview
This Kaggle competition task is created on the MD.ai platform in collaboration with the Radiological Society of North America (RSNA) and the American Society of Neuroradiology (ASNR).
https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/

## Getting Started

## Mask RCNN

Mask RCNN (regional convolutional neural network) contains consists of two stages. The first stages scans the image and generates proposals(areas likely to contain an object). And the second stage in parallel classifies the proposals and generates bounding boxes and masks.
![Image of Mask R-CNN framework](https://github.com/jhihan/rsna_pneumonia_detection/blob/master/images/mask_rcnn_framework.png)
## Requirements of Mask
Python 3.4, TensorFlow 1.3 (but < 2.0), Keras 2.0.8 and other common packages listed in requirements.txt of Mask RCNN packages developed by Waleed Abdulla.
## Installation
Follow the instruction in https://github.com/matterport/Mask_RCNN.
