# Natural Scene Image Classification Using CNN

## Project Overview

This project applies a Convolutional Neural Network (CNN) to classify natural scene images into six categories using a dataset of images with dimensions of 150 × 150 pixels.

## Dataset

The dataset contains six scene categories:

- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

The dataset is organized into separate folders for training, testing, and prediction.

## Methodology

1. Extracted and inspected the image dataset.
2. Preprocessed images by resizing and normalizing pixel values.
3. Built and trained a CNN model for six-class image classification.
4. Evaluated model performance using appropriate classification metrics.
5. Explored model improvement techniques, such as data augmentation, dropout, and hyperparameter tuning.
6. Used the trained model to predict scene categories for unseen images.

## Technologies

- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Objective

To develop an effective deep learning model for natural scene classification and improve its performance through CNN architecture optimization and training techniques.

## Dataset Categories

| Label | Category |
|---|---|
| 0 | Buildings |
| 1 | Forest |
| 2 | Glacier |
| 3 | Mountain |
| 4 | Sea |
| 5 | Street |

## Expected Outcome

A trained CNN model capable of predicting one of the six natural scene categories from an input image. Model performance is assessed using test-set metrics and classification results.

## How to Run

1. Open the notebook in Google Colab.
2. Upload or mount Google Drive containing `classification.zip`.
3. Extract the dataset and verify the training, testing, and prediction folders.
4. Run the preprocessing, model training, evaluation, and prediction cells.

**Note:** Actual accuracy and performance improvements should be added after running the experiments.
