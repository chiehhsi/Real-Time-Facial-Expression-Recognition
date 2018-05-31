# Real Time Facial Expression Recognition

This projects uses Keras with Tensorflow Backend and OpenCV to develop a Convolutional Neural Network which can classify, from an image or from a real time video feed (webcam), the emotion/expression that a person is showing. The CNN was trained on 90% of a combination of the CK+, JAFFE and the KDEF datasets for 40 epochs. The remaining 10% was used as the test set to check the validation accuracy of the model (70%).

Capture of the live video feed from the webcam and processing that video feed was done using OpenCV. Face detection was implemented using the dnn module of OpenCV.

Work Environment: i7 4510U, 8 GB RAM, Geforce 840M 2GB
IDE used: Spyder (Anaconda)
Model trained using Google Colaboratory

# Instructions

Run webcam.py from the command prompt to get FER in real time from webcam.

Eg. >> python webcam.py

Run webcam.py with your test image in the same folder as the code files giving your test image as a command line argument

Eg. >> python webcam.py -testImage test_img.png
