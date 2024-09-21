# Crop Detection and Counting

## Overview

This project focuses on detecting and counting crops in images using advanced computer vision techniques. By leveraging a trained YOLO (You Only Look Once) model, this application automates the process of identifying and quantifying crops in static images, providing valuable insights for agricultural analysis and management.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Technologies Used](#technologies-used)
4. [Features](#features)
5. [Installation](#installation)
6. [Usage](#usage)
7. [Results](#results)
8. [Screenshots](#screenshots)
9. [Contributing](#contributing)
10. [License](#license)

## Introduction

Crop detection and counting are critical components of precision agriculture, allowing farmers and researchers to assess crop health and yield efficiently. This project utilizes a YOLO model for real-time object detection, enabling accurate localization and counting of crops in images.

## Dataset

The dataset used for training and testing consists of images of various crops. Each image is annotated with bounding boxes indicating the locations of the crops. The dataset should be organized in a structured manner, typically in the following format:


## Technologies Used

- **Python**: The programming language used for implementation.
- **OpenCV**: A library for computer vision tasks, including image processing and visualization.
- **YOLOv8**: Pre-trained models for real-time object detection.
- **TensorFlow / PyTorch**: Deep learning frameworks used for model training and inference.
- **NumPy**: A library for numerical operations.

## Features

- **Real-Time Crop Detection**: Detects and counts crops in images using a YOLO model.
- **Bounding Box Visualization**: Draws bounding boxes around detected crops for easy visualization.
- **Data Logging**: Saves detection results, including crop counts, to a CSV file for analysis.
- **Performance Metrics**: Provides evaluation metrics such as precision, recall, and F1 score.

## Installation

1. **Install Python**: Ensure Python is installed on your system. Download it from [python.org](https://www.python.org/downloads/).
2. **Install Required Libraries**:
   ```bash
   pip install opencv-python numpy tensorflow # or torch for PyTorch

![val_batch1_labels](https://github.com/user-attachments/assets/d0e07bf9-8e5f-4e96-a0c9-2294db1b6732)
![val_batch1_labels (1)](https://github.com/user-attachments/assets/56aa4f5a-f554-4c66-92e6-ea013dc0a291)
![val_batch0_pred](https://github.com/user-attachments/assets/4b4d3e52-8c67-4366-a8e8-4d09ced8377b)
![train_batch882](https://github.com/user-attachments/assets/c34c25f0-ff38-4bfc-9615-92457dea9d93)
