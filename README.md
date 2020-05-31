# RSNA Pneumonia Detection Challenge
## Overview
This Kaggle competition task is created on the MD.ai platform in collaboration with the Radiological Society of North America (RSNA) and the American Society of Neuroradiology (ASNR).
https://www.kaggle.com/c/rsna-pneumonia-detection-challenge/

## Getting Started

## Mask RCNN

Mask RCNN (regional convolutional neural network) contains consists of two stages. The first stages scans the image and generates proposals(areas likely to contain an object). And the second stage in parallel classifies the proposals and generates bounding boxes and masks.

In addition to the existing branch for classification and bounding box regression in the original RCNN, Mask RCNN adds a branch for predicting segmentation masks on each Region of Interest (RoI) (Figure \ref{MRCNN_framework}). The mask branch is a small FCN applied to each RoI, predicting a segmentation mask in a pixel-topixel manner.
![Image of Mask R-CNN framework\label{MRCNN_framework}](https://github.com/jhihan/rsna_pneumonia_detection/blob/master/images/mask_rcnn_framework.png)
*The Mask R-CNN framework for instance segmentation. Source: https://arxiv.org/abs/1703.06870*
## Requirements of Mask
Python 3.4, TensorFlow 1.3 (but < 2.0), Keras 2.0.8 and other common packages listed in requirements.txt of Mask RCNN packages developed by Waleed Abdulla.
## Installation
Follow the instruction in https://github.com/matterport/Mask_RCNN.
