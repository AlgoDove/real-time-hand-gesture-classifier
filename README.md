Real Time Hand Gesture Classifier

This is a real-time hand gesture recognition system that detects three custom gestures: GOD, LOVE, and YOU. The project was built from scratch using webcam input, a custom-trained Convolutional Neural Network (CNN), and Google Colab. The goal is to explore gesture-based interaction and support non-verbal communication, especially for the deaf and hard-of-hearing community.


Features

Real-time gesture detection using webcam
Custom dataset created using webcam
CNN model built and trained in Google Colab
Live prediction with TensorFlow and OpenCV
Focused on accessibility and communication

Technologies Used

Python
TensorFlow
Keras
OpenCV
Google Colab

Model Details

Three gesture classes: God, loves, you
Image size: 64x64 pixels
Two convolution layers with ReLU and MaxPooling
Dense layer followed by softmax output
Trained on 25 images per gesture
Achieved over 90 percent accuracy on validation set

How It Works

Capture your own hand gesture images using webcam
Train the CNN model using Keras in Google Colab
Save the model as gesture_model.h5
Use webcam input again to test the model with real-time prediction

Files Included

gesture_classifier.ipynb — Full Colab notebook for training and prediction
gesture_model.h5 — Trained model file
gesture_dataset — (Optional) Folder structure for training images


