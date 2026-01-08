# Star–Galaxy Binary Classification using CNN

## Overview

This project implements a **Convolutional Neural Network (CNN)** to perform **binary classification of astronomical objects**, distinguishing **stars** from **galaxies** using image data.  
The project focuses on applying deep learning techniques to scientific image datasets, emphasizing preprocessing, model design, and evaluation.

Such classification tasks are fundamental in observational astronomy and large-scale sky surveys, where automated object identification is necessary due to data scale.

## Problem Statement

Given astronomical images of celestial objects, classify each image as either:
- **Star**
- **Galaxy**

This is formulated as a supervised binary classification problem.

## Dataset

- Labeled astronomical image dataset containing stars and galaxies
- Images preprocessed and resized for CNN compatibility
- Dataset split into training, validation, and test sets

*(Dataset source can be added here if applicable)*

## Methodology

- Implemented a **CNN using TensorFlow/Keras**
- Spatial features such as intensity distribution and structure are learned directly from image data
- Binary classification performed using a sigmoid output layer

### Key Steps
- Image normalization
- (Optional) data augmentation
- CNN-based feature extraction
- Optimization using binary cross-entropy loss
- Evaluation on unseen test data

## Model Architecture (High-Level)

- Convolutional layers with ReLU activation
- Max-pooling layers for dimensionality reduction
- Fully connected layers for classification
- Sigmoid activation for binary output

## Results

- Effective separation between stars and galaxies
- Performance evaluated using:
  - Accuracy
  - Training vs validation loss curves
  - Confusion matrix (if implemented)

## Technologies Used

- **Python**
- **TensorFlow / Keras**
- **NumPy**
- **Matplotlib** (for visualization)
