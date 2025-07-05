# Internship Project – CRISTaL Laboratory

**Author:** Léonard Havet  
**Contact:** leonard.havet@gmail.com

## Overview

This document briefly introduces the project carried out during my internship at the **CRISTaL Laboratory** (Centre de Recherche en Informatique, Signal et Automatique de Lille).

The main objective of the project is to **automatically map all containers in a port** using aerial or fixed-camera imagery. The challenge lies in accurately detecting, segmenting, and localizing containers in 3D space from video sequences or single views.

## Approach and Tools

To achieve this, the pipeline combines several state-of-the-art computer vision techniques:

- **YOLO** (You Only Look Once) for fast and accurate object detection.
- **SAM** (Segment Anything Model) to extract precise object masks based on the bounding boxes.
- **Clustering algorithms** (e.g., DBSCAN, K-Means, hierarchical clustering) to group detections, refine object instances across multiple frames or views, and improve consistency.
- **Geometric reasoning** to estimate 3D positions of containers when multiple views are available.
- **Simulation** of the port and camera scenarios using the **Godot Engine**, providing a reproducible and flexible testing environment.

## Current Status

The complete README, including a detailed explanation of the pipeline, experiments, evaluation metrics, and results, will be published here **after the end of my internship** (in a few weeks).

*This document is a placeholder. A full technical report will follow.*
