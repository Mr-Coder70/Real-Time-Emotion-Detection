# Real-Time-Emotion-Detection
This project implements a Real-Time Emotion Detection System using Computer Vision and Deep Learning. The system captures live video from a webcam, detects faces in real time, and classifies facial expressions into predefined emotion categories using a trained Convolutional Neural Network (CNN) model.

The application demonstrates the practical integration of OpenCV, TensorFlow/Keras, and Deep Learning techniques for real-time inference.

Key Features

Real-time face detection using Haar Cascade Classifier

Emotion classification using a trained CNN model (.h5)

Live emotion label display on webcam feed

Lightweight and efficient implementation

Exit functionality using keyboard input (q key)

Technologies Used

Python

OpenCV

TensorFlow

Keras

NumPy

Deep Learning (CNN)

System Architecture

Capture live video stream from webcam

Convert frames to grayscale

Detect faces using Haar Cascade classifier

Resize detected face to 48×48 pixels

Normalize pixel values

Pass image to trained CNN model

Predict emotion category

Display emotion label on the video frame

Emotions Detected

Angry

Happy

Neutral

Sad

Surprised

Future Enhancements

Improve model accuracy with larger dataset

Add more emotion categories

Display prediction confidence score

Deploy as a web-based application

Optimize performance for low-resource systems
