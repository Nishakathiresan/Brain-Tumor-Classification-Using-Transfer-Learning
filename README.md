# Brain Tumor Classification Using Transfer Learning
A Deep Learning project for brain tumor classification using Transfer Learning with ResNet50 and MRI images.
## Project Overview

This project uses Deep Learning and Transfer Learning techniques to classify brain MRI images into tumor and non-tumor categories. A pre-trained ResNet50 model is used as the feature extractor, while custom classification layers are added to improve prediction performance on MRI images.

## Problem Statement

Early detection of brain tumors is important for effective treatment. Manual MRI analysis can be time-consuming and depends on expert radiologists. This project demonstrates how transfer learning can assist in automatic brain tumor classification.

## Features

- Brain MRI image classification
- Transfer Learning using ResNet50
- Frozen convolutional layers
- Custom classification layers
- Model evaluation using Precision, Recall, F1-Score
- Confusion Matrix analysis

## Technologies Used

- Python
- TensorFlow
- Keras
- ResNet50
- NumPy
- Scikit-learn
- Google Colab

## Dataset

Dataset Source:
https://www.kaggle.com/datasets/preetviradiya/brian-tumor-dataset

## Model Workflow

1. Download MRI dataset
2. Load pre-trained ResNet50 model
3. Freeze base model layers
4. Add custom dense layers
5. Train the model
6. Predict tumor classes
7. Evaluate using classification metrics

## Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

## Future Enhancements

- Brain Tumor Segmentation
- Grad-CAM Visualization
- Multi-Class Tumor Classification
- EfficientNet Implementation
## Project Output

The following images demonstrate the model's performance and evaluation results.

- Model Summary
- Classification Report
- Confusion Matrix
- Prediction Results
