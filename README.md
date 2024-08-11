# Face-Detection-with-OpenCV-and-dlib

This project demonstrates how to perform real-time face detection using OpenCV and dlib libraries in Python. The application captures video from the default camera, detects faces in the frames, and displays the number of detected faces along with bounding boxes around them.

## Features
- Real-time face detection using dlib's frontal face detector.
- Bounding boxes drawn around detected faces.
- Face numbers labeled on the bounding boxes.
- Real-time video feed from the default camera.

## Prerequisites
Before running the script, ensure you have the following libraries installed:

- OpenCV
- dlib
- numpy

## Script Overview
The script does the following:

### 1. Imports Libraries:
- cv2 for handling video capture and image processing.
- numpy for numerical operations.
- dlib for face detection.

### 2. Initializes Video Capture:
- Captures video from the default camera.

### 3. Face Detection:
- Converts each frame to grayscale.
- Uses dlib's frontal face detector to detect faces.
- Draws bounding boxes around detected faces.
- Labels each detected face with a number.

### 4. Display and Exit:
- Displays the processed video feed.
- Exits when the 'q' key is pressed.
