# PCB Defect Detection using YOLOv5

Author: Dimitri Vavoulis

## Project Overview
This project presents an automated system for detecting defects in Printed Circuit Boards (PCBs) using computer vision and deep learning techniques. The core of the system is a custom-trained YOLOv5 model, designed to identify and localize various types of PCB defects with high accuracy and speed.

The workflow encompasses:

1. Data Preparation: Utilizing a specialized PCB defect dataset, processed and augmented using Roboflow.
2. Model Training: Fine-tuning a YOLOv5 model on the prepared dataset to recognize specific PCB defects.
3. Inference: Applying the trained model to detect defects in both static images and video streams.
4. Analysis: Generating statistical insights and visualizations of the detected defects.
5. Real-time Processing: Implementing a video processing pipeline for continuous defect detection.

This system is designed to enhance quality control processes in PCB manufacturing, offering a scalable solution that can be integrated into existing production lines for real-time defect identification and analysis.
