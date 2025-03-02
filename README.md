# ORL-PCA Face Recognition

## Overview
This project implements a face recognition system using Principal Component Analysis (PCA) on the ORL (Olivetti Research Laboratory) face dataset. PCA is employed for dimensionality reduction and feature extraction, enabling efficient recognition of faces.

## Features
- Utilizes PCA for dimensionality reduction.
- Implements face recognition on the ORL dataset.
- Uses eigenfaces for feature representation.
- Performs classification based on nearest neighbor approaches.
- Provides visualization of eigenfaces and reconstructed images.

## Requirements
To run this project, ensure you have the following dependencies installed:
- Python 3.x
- NumPy
- OpenCV
- Matplotlib
- Scikit-learn

You can install the required dependencies using:
```bash
pip install numpy opencv-python matplotlib scikit-learn
```

## Dataset
The ORL face dataset consists of 400 grayscale images of 40 individuals (10 images per person). Each image has a resolution of 92x112 pixels. The dataset can be downloaded from:
[ORL Face Database](https://www.kaggle.com/datasets/kasikrit/att-database-of-faces)

## Usage
1. Load the dataset and preprocess the images.
2. Perform PCA to extract principal components.
3. Project face images onto the PCA subspace.
4. Classify test images using a nearest neighbor classifier.
5. Evaluate the recognition performance.

Run the Jupyter Notebook to execute the face recognition pipeline:
```bash
jupyter notebook "ORL-PCA Face Recognition.ipynb"
```

## Results
- The PCA-based face recognition system achieves a high recognition rate by reducing the feature space while retaining essential facial features.
- Eigenfaces representation provides insight into the most significant features contributing to face recognition.

## Acknowledgments
This project is inspired by classical face recognition approaches using PCA and eigenfaces.


