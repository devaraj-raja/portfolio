---
title: Water Body Semantic Segmentation using GeoAI
description: Semantic segmentation of water bodies from satellite imagery using a U-Net deep learning model built with the GeoAI framework.
image: assets/images/profile.png
tags:
  - GeoAI
  - Semantic Segmentation
  - Deep Learning
  - U-Net
  - Remote Sensing
  - Python
---

# Water Body Semantic Segmentation using GeoAI

## Overview

This project demonstrates semantic segmentation of water bodies from satellite imagery using the GeoAI framework. A U-Net model with a ResNet34 encoder was trained to classify each pixel as either water or background, enabling accurate extraction of water bodies from remote sensing imagery.

## Key Features

- Semantic segmentation of water bodies
- U-Net architecture with ResNet34 encoder
- Pixel-wise classification
- Model training and evaluation
- Prediction on unseen satellite images
- Visualization of segmentation results

## Project Workflow

1. Prepare satellite images and segmentation masks.
2. Train the U-Net segmentation model.
3. Evaluate model performance.
4. Perform semantic segmentation inference.
5. Compare predictions with ground truth masks.
6. Visualize segmentation outputs.

## Technologies Used

- Python
- GeoAI
- U-Net
- ResNet34
- PyTorch
- Jupyter Notebook

## Dataset

- **Source:** Water body segmentation dataset
- **Task:** Semantic segmentation of water bodies
- **Classes:** Water and Background

## Results

![Project overview image](../assets/images/placeholder-project.png)

<!-- Performance metrics, IoU, Dice Score, Precision, Recall, and sample prediction images will be added later. -->

## Future Improvements

- Train for additional epochs to improve segmentation accuracy.
- Experiment with different encoder architectures.
- Apply data augmentation techniques.
- Extend the model to segment additional land cover classes.
- Deploy the model for large-scale satellite image inference.