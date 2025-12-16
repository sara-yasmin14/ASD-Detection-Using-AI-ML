# Autism Spectrum Disorder Detection Using Machine Learning

This repository contains code and experiments from my MPhil research focused on
early detection of Autism Spectrum Disorder (ASD) using machine learning and
computational analysis of hand-drawn shapes.

## Overview
Early diagnosis of ASD is challenging due to reliance on clinical expertise and
time-consuming behavioral assessments. This work explores automated, data-driven
screening approaches by analyzing neuro-behavioral patterns present in simple
drawing tasks.

## Methods
- Image preprocessing (normalization, noise reduction, augmentation)
- Feature extraction:
  - Local Binary Patterns (LBP)
  - Histogram of Oriented Gradients (HOG)
  - Optimization-based feature selection (HHO, GWO)
- Machine learning models:
  - Random Forest
  - Naive Bayes
  - Decision Tree
  - Hoeffding Tree
  - Bagging
- Model evaluation using accuracy, precision, recall, and F1-score

## Tools and Technologies
- Python
- NumPy, OpenCV
- scikit-learn
- Matplotlib

## Dataset
The dataset consists of hand-drawn shapes collected from ASD and neurotypical
participants. Raw data is not publicly shared due to privacy and ethical
constraints.

## Motivation
This project aims to bridge machine learning and neuroscience by developing
transparent and computationally efficient screening tools for neurodevelopmental
disorders.

## Note
This repository is intended for academic and research demonstration purposes.
