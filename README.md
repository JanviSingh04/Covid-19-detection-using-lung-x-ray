This project focuses on detecting COVID-19 infection from chest X-ray images using machine learning and deep learning techniques. The system classifies lung X-ray images into three categories:

COVID-19 Positive
Normal
Pneumonia

The objective is to assist in early and automated diagnosis using a fast, non-invasive, and AI-driven approach.
The dataset is provided in a ZIP format and must be downloaded and extracted before running the project.

Dataset Setup Steps
Download the dataset ZIP file
Extract the ZIP file
Place the extracted folder inside the project root directory

project-root/
│
├── data/
│ ├── covid/
│ ├── normal/
│ ├── pneumonia/
│
├── src/
├── main.py
├── requirements.txt
└── README.md

Technologies Used
Python
TensorFlow / Keras
NumPy
OpenCV
Matplotlib
Scikit-learn

Methodology


The project follows a deep learning pipeline:
Data loading and preprocessing
Image resizing and normalization
Data augmentation to improve generalization
CNN-based model training
Model evaluation and performance analysis

The model is built using a Convolutional Neural Network (CNN) that automatically extracts features from X-ray images to classify lung conditions.
