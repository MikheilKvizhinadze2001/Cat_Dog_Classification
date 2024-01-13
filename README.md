# Cat vs Dog Image Classification

This repository contains the code for a machine learning project that classifies images of cats and dogs. The project explores the application of various machine learning models, including Logistic Regression, Random Forest, and a pre-trained Convolutional Neural Network (CNN) model, VGG16.

## Project Overview

The goal of this project is to build a model that can accurately classify images of cats and dogs. The project starts with a simple Logistic Regression model, moves on to a more complex Random Forest model, and finally uses a pre-trained VGG16 model.

## Models

1. **Logistic Regression**: A simple and fast model that serves as a baseline for the task. However, due to the high dimensionality and complexity of image data, it does not perform well on this task.

2. **Random Forest**: A more complex model that unfortunately overfits the training data. Techniques such as hyperparameter tuning could be used to improve its performance.

3. **VGG16**: A pre-trained CNN model that performs the best among the three models. However, it underfits the data, indicating the model's simplicity. Increasing model complexity and unfreezing some layers of the VGG16 model could potentially improve its performance.

## Results

The results of the project are documented in the Jupyter notebook. In summary, while the Logistic Regression and Random Forest models struggle with the complexity of the task, the VGG16 model shows promise and could be improved with further tuning.


Link to the dataset: https://www.kaggle.com/datasets/karakaggle/kaggle-cat-vs-dog-dataset
Link to the model: https://drive.google.com/file/d/11wVgiYdZHIgjVzS9DH_yAhUJeBCatPNF/view?usp=drive_link
