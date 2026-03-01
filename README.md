# Brain Tumor Detection Using Deep Learning

### MRI Image Classification with Convolutional Neural Networks and Streamlit Interface

------------------------------------------------------------------------

## Overview

This project implements an automated **brain tumor detection system**
using deep learning techniques applied to MRI images. The goal is to
assist early diagnosis by classifying MRI scans into tumor and non‑tumor
categories using a Convolutional Neural Network (CNN).

In addition to model training, a **Streamlit-based graphical interface**
is developed to simulate a computer‑aided diagnosis (CAD) tool, allowing
users to upload an MRI image and receive an instant prediction.

The project demonstrates how AI can support radiological screening
workflows by reducing manual effort and assisting medical professionals
in preliminary analysis.

------------------------------------------------------------------------

## Motivation

Brain tumors are life‑threatening conditions where **early detection
significantly improves survival rate and treatment effectiveness**.
Manual MRI analysis:

-   requires expert radiologists
-   is time‑consuming
-   is prone to human fatigue and subjectivity

Deep learning models can act as a **decision‑support system**, not
replacing doctors, but helping them detect suspicious cases faster.

------------------------------------------------------------------------

## Objectives

-   Develop a CNN model for MRI image classification
-   Distinguish tumor vs non‑tumor brain scans
-   Evaluate classification performance using metrics
-   Provide an interactive interface for prediction
-   Demonstrate a practical healthcare AI application

------------------------------------------------------------------------

## Methodology

### 1. Data Preprocessing

The MRI images undergo: - resizing - normalization - noise reduction -
labeling

Preprocessing ensures consistent input for neural network training and
improves convergence stability.

------------------------------------------------------------------------

### 2. Convolutional Neural Network (CNN)

The model learns spatial features directly from images using:

-   Convolution layers (feature extraction)
-   Activation functions (non‑linearity)
-   Pooling layers (dimensionality reduction)
-   Fully connected layers (classification)

The CNN automatically learns: - tumor texture patterns - abnormal tissue
regions - structural irregularities

------------------------------------------------------------------------

### 3. Model Training

The dataset is divided into: - training set - validation set - testing
set

The network learns to minimize classification error using
backpropagation and iterative weight updates.

------------------------------------------------------------------------

### 4. Streamlit Interface

A web interface is created where a user can:

1.  Upload an MRI scan
2.  Run prediction
3.  View classification output instantly

This simulates a real‑world **clinical decision support application**.

------------------------------------------------------------------------

## Project Workflow

1.  Load MRI dataset
2.  Preprocess images
3.  Train CNN model
4.  Evaluate performance
5.  Save trained model
6.  Launch Streamlit interface
7.  Upload new MRI image for prediction

------------------------------------------------------------------------

## Output

The system predicts:

-   **Tumor Detected** or
-   **No Tumor Detected**

The prediction is generated in real‑time through the interface.

------------------------------------------------------------------------

## Performance Evaluation

The model is evaluated using:

-   Accuracy
-   Confusion Matrix
-   Precision
-   Recall
-   F1‑Score

These metrics measure reliability and clinical usefulness of the
classifier.

------------------------------------------------------------------------

## Requirements

Python 3.x

Libraries: - numpy - matplotlib - tensorflow / keras - opencv-python -
scikit-learn - streamlit - pillow

Install dependencies:

    pip install -r requirements.txt

------------------------------------------------------------------------

## Running the Project

Clone repository:

    git clone https://github.com/HariniKartheeswaran/Brain-Tumor-Detection.git
    cd Brain-Tumor-Detection

Train / Test model: Run the notebook sequentially.

Launch interface:

    streamlit run app.py

Open browser: http://localhost:8501

Upload an MRI image and view prediction.

------------------------------------------------------------------------

## Applications

-   Radiology screening assistance
-   Hospital triage systems
-   Telemedicine platforms
-   Medical education demonstrations

------------------------------------------------------------------------

## Limitations

-   Not a substitute for clinical diagnosis
-   Dependent on dataset quality
-   Limited dataset diversity
-   Requires further validation for real clinical deployment

------------------------------------------------------------------------

## Future Improvements

-   Multi‑class tumor classification
-   Tumor segmentation (location detection)
-   3D MRI volume analysis
-   Explainable AI (heatmaps / Grad‑CAM)
-   Integration with hospital PACS systems

------------------------------------------------------------------------

## Research Domain

-   Medical Image Analysis
-   Computer Vision
-   Deep Learning
-   Computer‑Aided Diagnosis (CAD)
