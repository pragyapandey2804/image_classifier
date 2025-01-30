# Image Classifier using SVM

This project implements an image classification model using Support Vector Machine (SVM) to classify images into two categories: 'empty' and 'not_empty'. The model is trained using scikit-learn and is evaluated based on the accuracy of predictions on a test set.

## Features

- **Data Preparation**: Images are loaded from the specified directory, resized to 15x15 pixels, and flattened to create feature vectors.
- **Model Training**: Support Vector Machine (SVM) classifier is used for training with hyperparameter optimization using GridSearchCV.
- **Model Evaluation**: The model is evaluated using accuracy score.
- **Model Saving**: The trained model is saved as a pickle file for later use.

## Requirements

- Python 3.x
- scikit-image
- scikit-learn
- numpy
- pickle

You can install the required dependencies with pip:

```bash
pip install scikit-image scikit-learn numpy
```




