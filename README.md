# Deep Convolutional GAN for Minority Class Oversampling in Medical Image Classification

## Overview
This project explores the use of **Deep Convolutional Generative Adversarial Networks (DCGANs)** to address class imbalance in medical image classification. Using grayscale chest X-ray images, the model generates synthetic samples to augment minority-class data and evaluates their impact on classification performance.

## Key Features
- Implemented DCGAN to generate synthetic chest X-ray images.
- Applied GAN-based oversampling to address class imbalance.
- Compared classification performance using original and augmented datasets.
- Evaluated multiple machine learning and deep learning classifiers.
- Analyzed model performance using ROC-AUC and other classification metrics.

## Models Evaluated
- Artificial Neural Network (ANN)
- Convolutional Neural Network (CNN)
- Decision Tree
- Random Forest
- Naive Bayes
- Support Vector Machine (SVM)

## Technology Stack
Python, PyTorch, Scikit-learn, OpenCV, NumPy, Pandas, Matplotlib.

## Workflow
1. Preprocessing grayscale chest X-ray images.
2. Training DCGAN to generate synthetic medical images.
3. Augmenting the original dataset with generated samples.
4. Training classifiers on original and augmented datasets.
5. Comparing classification performance to assess the impact of synthetic data augmentation.

## Objective
Investigate the effectiveness of GAN-based synthetic data generation in mitigating class imbalance and improving medical image classification performance.
