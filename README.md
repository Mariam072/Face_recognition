# Face_recognition
face_recognition_project that generate datasets ,train it and start detecting the known faces by their names
Face Recognition Project Summary
Data Collection

Uses webcam to capture facial images

Crops faces, converts to grayscale, and saves in /data folder

Images named as user.[ID].[number].jpg (e.g., user.1.1.jpg)

Model Training

Reads images from /data and converts to numeric arrays

Uses LBPH (Local Binary Patterns Histograms) algorithm for feature extraction

Saves trained model as classifier.xml

Real-Time Recognition

Detects faces in video frames using webcam

Compares detected faces with trained model to calculate confidence score

Displays "Mariam Hassan" if confidence >77%, otherwise "Unknown"
