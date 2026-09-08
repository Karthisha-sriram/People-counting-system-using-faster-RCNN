# People Counting System Based on Head Detection Using Faster R-CNN

## Overview

This project implements a computer vision-based people counting system using Faster R-CNN (Region-based Convolutional Neural Network) for human head detection.

The system detects human heads in images and uses the detected regions to estimate the number of people present in a scene. The project demonstrates the application of deep learning and object detection techniques to crowd analysis.

## Features

* Human head detection using Faster R-CNN
* Automatic people counting from images
* Image-based object detection
* Visual representation of detected heads
* Sample test images included for evaluation
* Python-based implementation

## Technologies Used

* Python
* Faster R-CNN
* Deep Learning
* Computer Vision
* Object Detection
* Image Processing

## Project Structure

```text
People-counting-system-using-faster-RCNN/
│
├── FRCNNHeadCount.py
├── requirements.txt
├── run.bat
├── test.jpg
│
└── testImages/
    ├── 1.jpg
    ├── 2.jpg
    ├── 3.jpg
    ├── 4.jpg
    ├── download.jpg
    └── download1.jpg
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/Karthisha-sriram/People-counting-system-using-faster-RCNN.git
```

### Navigate to the Project Directory

```bash
cd People-counting-system-using-faster-RCNN
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Usage

Run the Python application:

```bash
python FRCNNHeadCount.py
```

Alternatively, the project can be executed using the provided batch file:

```bash
run.bat
```

## Test Data

The repository contains six sample images in the `testImages` directory. These images can be used to test the head detection and people counting functionality.

## Applications

The approach demonstrated in this project can be applied to:

* Crowd monitoring
* People counting
* Public-space analysis
* Occupancy estimation
* Event monitoring
* Smart surveillance systems

## Objective

The objective of this project is to demonstrate how deep learning-based object detection can be used to detect human heads and estimate the number of people present in an image.

## Author

**Karthisha Sriram**

GitHub: https://github.com/Karthisha-sriram
