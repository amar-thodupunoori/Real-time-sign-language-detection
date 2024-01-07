# Real-Time Sign Language Detection

## Overview
This project implements object detection and recognition using TensorFlow and the TensorFlow Object Detection API. It involves setting up paths, creating label maps, generating TF records, and training a custom model based on the SSD Mobilenet architecture. Additionally, real-time detection is showcased, and an interactive script for collecting labeled images is provided.

## Files

### 1. `tutorial.ipynb`
   - **Resources Used:** Downloads required scripts and sets up the necessary paths.
   - **Steps:**
     - Set up paths and download necessary resources.
     - Create a label map for the custom classes.
     - Generate TF records for training and testing.
     - Download a pre-trained model from the TensorFlow Model Zoo.
     - Copy model config for training and update it for transfer learning.
     - Train the model and load it from the checkpoint.
     - Detect objects in real-time using a webcam.

### 2. `untitled.ipynb`
   - **Functionality:** Python script for collecting labeled images.
   - **Steps:**
     - Capture images for each label in real-time using a webcam.
     - Images are stored in the specified directory for later training.

### 3. `a.py`
   - **Functionality:** Real-time object detection and recognition script.
   - **Steps:**
     - Utilizes the trained model to recognize and display labeled objects in real-time through a webcam.
     - Detects custom classes (A-Z, space, dot) and forms a string accordingly.

## Instructions
1. Follow the setup instructions in `tutorial.ipynb` to prepare the environment.
2. Run the steps in `tutorial.ipynb` for creating a label map, generating TF records, and training the model.
3. Use `untitled.ipynb` to collect labeled images for custom classes.
4. Run `a.py` to initiate real-time object detection and recognition.

Feel free to explore and modify the code for experimentation. Enjoy detecting and recognizing objects with the trained model!
