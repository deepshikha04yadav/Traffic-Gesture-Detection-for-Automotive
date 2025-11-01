# Traffic Police Gesture Recognition for Smart Automotive Systems

## Overview

This project aims to develop an AI-powered gesture recognition system capable of detecting and interpreting traffic police hand and body gestures in real-world road environments. The system can assist autonomous vehicles, ADAS systems, and smart traffic management setups in understanding human signals — especially in scenarios where traffic lights fail or manual control is required.

The model uses a combination of object detection and pose estimation techniques to identify a person (traffic police) and classify their gestures such as Stop, Go, Turn Left, or Turn Right.

## Key Features

* Detects traffic police or human controllers in outdoor scenes.
* Recognizes body and hand gestures relevant to traffic management.
* Built using modern deep learning architectures (e.g., YOLOv11, MediaPipe, or OpenPose).
* Designed for real-time inference on embedded or automotive systems.
* Potential integration with ADAS, smart cameras, or city surveillance systems.

## Dataset

The model is trained and evaluated using the Traffic Police Gesture Dataset available on Kaggle.
This dataset contains images of traffic police performing various hand gestures commonly used to direct traffic.

## Tech Stack

* Python
* YOLOv11 / YOLOv8 for object detection
* MediaPipe / OpenPose for body and hand keypoint detection
* TensorFlow / PyTorch for gesture classification
* OpenCV for image preprocessing and visualization

## Author
Developed by Deepshikha Yadav
