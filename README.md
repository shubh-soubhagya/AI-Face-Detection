# AI-Face-Detection

Face detection is a fundamental task in computer vision with numerous applications ranging from security and surveillance to photography and social media. This repository contains a simple yet effective face detection model implemented in Python using the OpenCV library. The model leverages a pre-trained Haar cascade classifier to detect faces in real-time through a webcam feed. This README provides an overview of how the model works, instructions for usage, guidelines for contributing, and licensing information.

## Overview

The face detection model is built using the OpenCV library, a popular open-source computer vision and machine learning software library. OpenCV provides various tools and algorithms for image processing, including face detection. The model utilizes the cv2.CascadeClassifier class to load the pre-trained Haar cascade classifier for face detection. Haar cascades are machine learning-based classifiers trained to identify objects in images, and they have been widely used for face detection due to their simplicity and effectiveness.

The model captures video frames from the webcam using cv2.VideoCapture, converts them to grayscale, and then applies the face detection algorithm using the detectMultiScale method. This method detects faces by analyzing the intensity gradients in the grayscale image and identifying regions with similar patterns to human faces. Once faces are detected, the model draws rectangles around them on the original frames using OpenCV's drawing functions. The program continues to run in a loop, continuously capturing frames from the webcam, detecting faces, and updating the display in real-time. The loop terminates when the user presses the 'q' key on the keyboard.

## Usage

To use the face detection model:

1. Ensure you have Python installed on your system. If not, you can download and install it from the official Python website.
2. Install OpenCV using pip, the Python package manager. Open your terminal or command prompt and run the following command: ``` pip install opencv-python ```
3. Run the Python script ``` FACE_DETECTION_MODEL.ipynb ```
4. Position yourself in front of your webcam, and the model will start detecting your face in real-time. Detected faces will be outlined with rectangles drawn on the video feed.
5. To quit the program, simply press the ``` q ``` key on your keyboard.

## Do Follow me for more AI projects : https://github.com/shubh-soubhagya






