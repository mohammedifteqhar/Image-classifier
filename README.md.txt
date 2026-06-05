# Image Classifier using CNN (CIFAR-10)

## Overview
This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images from the CIFAR-10 dataset.

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset
The CIFAR-10 dataset contains 60,000 color images belonging to 10 classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

## Model Architecture
- Conv2D
- MaxPooling2D
- Conv2D
- MaxPooling2D
- Conv2D
- Flatten
- Dense
- Softmax Output Layer

## Project Structure

```text
Image Classifier
│
├── notebooks
├── images
├── models
├── README.md
└── requirements.txt
```

## Results
The model is trained on a subset of the CIFAR-10 dataset and evaluated using test accuracy.

## Future Improvements
- Data Augmentation
- Transfer Learning
- Hyperparameter Tuning