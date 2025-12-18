Road Signs Detection Dataset – Roboflow Annotation Project 

Overview

This project focuses on annotating road traffic sign images for object detection tasks.
The dataset includes multiple types of traffic signs captured from different angles,
distances, and real-world road scenarios. Annotations were created using Roboflow
and exported in TensorFlow Object Detection format.

Task Type

Object detection
Multi-class traffic sign recognition

Dataset Structure

The dataset is organized into two main folders.

The images/ folder contains subfolders for each traffic sign category. Each subfolder
includes multiple images of the same sign captured from different viewpoints.

The annotations/ folder contains annotation files in TensorFlow Object Detection
(JSON) format.

Traffic sign categories included in the dataset:
no entry
no u-turn
pedestrian crossing
roundabout
speed limit 40
speed limit 60
speed limit 80
stop
traffic light
turn left
turn right
yield

Each category contains approximately 8–10 images.

Annotated Classes and Labels

Each image contains bounding box annotations for traffic signs.
When additional signs or relevant road elements appeared in the same image,
they were also annotated to improve contextual understanding and model robustness.

Annotation Methodology

Bounding box annotation for each traffic sign instance
Multiple objects annotated per image when applicable
Consistent class naming across the dataset
Images reviewed to ensure annotation accuracy

Annotation Tool

Roboflow

Annotation Format

TensorFlow Object Detection
COCO-style JSON annotation structure

Annotation Output

Annotation files in JSON format
Stored in the annotations/ directory

Potential Applications

Traffic sign detection systems
Autonomous driving and ADAS research
Smart city and road infrastructure analysis
Educational object detection projects

Notes

This dataset was created for portfolio and educational purposes.