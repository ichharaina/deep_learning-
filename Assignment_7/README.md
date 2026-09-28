# Assignment 7 – Transfer Learning Using Pre-trained CNN Models

## Problem Statement

Implement transfer learning using pre-trained AlexNet, VGG16, ResNet50, and EfficientNetB0 models for image classification, and compare their performance.

## Objective

To understand and implement transfer learning using different CNN architectures and compare their performance for image classification.

## Dataset

The CIFAR-10 image classification dataset is used for the experiment.

## Models Implemented

The following CNN architectures are studied and compared:

1. AlexNet
2. VGG16
3. ResNet50
4. EfficientNetB0

## Implementation

The implementation includes:

- Loading and preprocessing the image dataset
- Resizing images according to the model input requirements
- Loading pre-trained CNN architectures
- Using pre-trained feature extraction layers
- Freezing the base model layers
- Adding a new classification layer
- Training the classification layers
- Evaluating the models
- Comparing model performance

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## Evaluation Metrics

The models are compared using:

- Test Accuracy
- Test Loss

## Result

The performance of AlexNet, VGG16, ResNet50, and EfficientNetB0 is compared using their test accuracy and test loss.

## Conclusion

Transfer learning allows a model trained on a large dataset to be adapted to a new image classification task. Different CNN architectures have different structures and feature extraction capabilities, which can result in different classification performance.

The experimental results are used to compare the performance of the implemented architectures.
