Breast Cancer Wisconsin (Diagnostic) Dataset

Overview

The Breast Cancer Wisconsin (Diagnostic) Dataset is a widely used dataset in medical and machine learning research. It is designed for binary classification, where the goal is to distinguish between malignant (cancerous) and benign (non-cancerous) tumors based on cell nucleus features. The dataset was originally provided by Dr. William H. Wolberg from the University of Wisconsin.
Dataset Characteristics

Type: Multivariate
Subject Area: Medical Research
Number of Instances: 569
Number of Features: 30
Feature Type: Real-valued (Floating-point)
Target Classes:
Malignant (Cancerous) – 212 instances
Benign (Non-cancerous) – 357 instances
Features Description

Each feature represents a characteristic of the cell nucleus extracted from digitized images of fine needle aspirates (FNA) of breast masses. The dataset includes:
Mean radius, texture, perimeter, and area
Smoothness, compactness, concavity, concave points
Symmetry and fractal dimension
These features are calculated for three different metrics:
Mean value
Standard error
Worst (largest) value
This results in 30 feature columns for each sample.
Prediction Task

The dataset is used to build classification models that can predict whether a breast tumor is malignant or benign based on the extracted cell features.
Applications

Breast cancer detection and diagnosis
Medical image analysis and feature extraction
Machine learning classification models (SVM, Random Forest, Neural Networks, etc.)
Healthcare AI and decision support systems
This dataset is often used as a benchmark for evaluating classification algorithms in medical and bioinformatics research.
