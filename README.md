# Handwritten Digit Recognition

## Project Overview
This project develops a computer vision classification system that recognizes handwritten digits from 0 to 9 using a Convolutional Neural Network (CNN).

## Problem Description
Handwritten digits in forms, records, and scanned documents may need to be converted into digital values. The system receives a handwritten digit image and returns the predicted digit class.

## Dataset & Model Used
The project uses the public scikit-learn Digits dataset with 1,797 grayscale 8 × 8 images from 10 classes (0–9). Pixel values are normalized to 0–1, and the dataset is split into training and testing sets using stratification. The model is a CNN with two convolutional blocks followed by fully connected layers.

## Workflow / Architecture
Input image → normalization → CNN convolution and pooling layers → fully connected layers → predicted digit.

The system diagram is available in `WORKFLOW.md`.

## Results & Evaluation
The executed notebook achieved an accuracy of **95.56%** on the held-out test set. The notebook reports Accuracy, Precision, Recall, and F1-score, displays a confusion matrix, and shows one successful prediction and one failure case. The model could be improved using a larger and more diverse dataset, data augmentation, and additional hyperparameter tuning.

## Technologies Used
Python, PyTorch, scikit-learn, NumPy, Matplotlib, and Jupyter Notebook.

## How to Run the Project
Open `handwritten_digit_recognition.ipynb` in Jupyter Notebook or Google Colab and run the cells from top to bottom. The notebook loads the dataset, preprocesses it, trains the CNN, evaluates the model, saves `digit_cnn_model.pth`, and demonstrates prediction.

## Future Improvements
Use a larger handwritten-digit dataset, apply data augmentation, and tune the CNN architecture and training hyperparameters.

## SDAIA Academy GitHub Repository Link
Add the GitHub repository link here after uploading the project.
