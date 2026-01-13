---
layout: page
title: Driver Monitoring System
description: Lightweight CNN-LSTM model for drowsiness and distraction detection
img: assets/img/driver-monitoring.jpg
importance: 4
category: work
github: https://github.com/subha-ilamathy/Driver-Monitoring-System-and-Helmet-Detection
---

## Problem
Traditional facial landmark-based driver monitoring systems fail without clear facial features. This limitation reduces reliability in real-world conditions with varying lighting, occlusions, or camera angles.

## Solution
Developed a lightweight CNN-LSTM model using visual cues (images) alone to detect drowsiness, distraction, and head pose without facial landmarks. The system works robustly across different conditions.

## Key Features
- **No Landmark Dependency**: Works without facial landmark detection
- **CNN-LSTM Architecture**: Combines spatial and temporal analysis
- **Real-time Processing**: Optimized for edge deployment
- **Multi-class Detection**: Drowsiness, distraction, and head pose

## Technical Implementation
- **Tech Stack**: TensorFlow, OpenCV, Computer Vision, Pose Estimation, Python
- **Model Architecture**: Custom CNN for feature extraction + LSTM for temporal analysis
- **Optimization**: Quantization and pruning for edge devices
- **Deployment**: Embedded systems and mobile devices

## Results
- Achieved high accuracy without facial landmarks
- Reduced computational requirements for edge deployment
- Improved robustness in challenging lighting conditions

**Company**: Multicoreware Inc  
**Duration**: Dec 2019 - Aug 2020  
**Repository**: [GitHub](https://github.com/subha-ilamathy/Driver-Monitoring-System-and-Helmet-Detection)
