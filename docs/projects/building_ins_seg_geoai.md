---
title: Building Instance Segmentation using GeoAI
description: Instance segmentation of buildings from aerial imagery using the GeoAI framework and Mask R-CNN.
image: assets/images/profile.png
tags:
  - GeoAI
  - Instance Segmentation
  - Mask R-CNN
  - Remote Sensing
  - Python
---

# Building Instance Segmentation using GeoAI

## Overview

This project demonstrates building instance segmentation from high-resolution aerial imagery using the GeoAI framework. A Mask R-CNN model was trained on building footprint data to detect individual buildings, generate segmentation masks, and convert predictions into vector polygons for geospatial analysis.

## Key Features

- Building instance segmentation
- Mask R-CNN deep learning model
- Training using building footprint annotations
- Prediction on unseen aerial imagery
- Polygon vectorization of detected buildings
- Visualization and geometric property analysis

## Project Workflow

1. Download aerial imagery and building footprint data.
2. Generate image tiles for model training.
3. Train the Mask R-CNN instance segmentation model.
4. Perform inference on test imagery.
5. Generate building masks.
6. Convert masks into GeoJSON polygons.
7. Calculate geometric properties and visualize results.

## Technologies Used

- Python
- GeoAI
- Mask R-CNN
- Raster Data Processing
- GeoPandas
- Matplotlib
- Jupyter Notebook

## Dataset

- **Source:** NAIP aerial imagery
- **Training Labels:** Building footprint GeoJSON
- **Task:** Building instance segmentation

## Results

![Project overview image](../assets/images/placeholder-project.png)

<!-- Performance metrics, prediction accuracy, and sample outputs will be added later. -->

## Future Improvements

- Improve segmentation accuracy using additional training data.
- Experiment with different backbone architectures.
- Support multi-class instance segmentation.
- Optimize inference for large-area aerial imagery.
- Deploy the workflow for automated building extraction.