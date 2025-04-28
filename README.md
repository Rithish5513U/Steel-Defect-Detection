# Steel-Defect-Detection

In this project, we use a simple CNN model to detect various defects on steel surfaces. The dataset consists of images with steel surface defects that are classified into different categories. Our model is trained to accurately classify these defects and provide predictions for unseen images.

## Steps

1. First the training dataset and test dataset has been stored to the csv file

2. This is used to map with the given train.csv file in the code

## Model Architecture

The model used in this project is a simple Convolutional Neural Network (CNN):

Convolutional Layer: Filters are applied to extract features from the images.

Max-Pooling: Down-sampling layers to reduce dimensionality and improve feature abstraction.

Flatten: Convert the 2D feature maps to 1D.

Fully Connected Layer: Dense layers to interpret the extracted features.

Output Layer: A softmax activation to classify the defect types.

## Results

The model achieves an accuracy of 86% on the test dataset.