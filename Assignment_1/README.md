# Assignment 1: MNIST Dataset Loading, Preprocessing and Visualization

## Aim

To load the MNIST handwritten digit dataset, preprocess the image data, split it into training and testing sets, and visualize the handwritten digits and class distribution.

---

## Dataset

The **MNIST (Modified National Institute of Standards and Technology)** dataset is a collection of handwritten digits from **0 to 9**.

Each image is:

- Grayscale
- Size: **28 × 28 pixels**
- Number of classes: **10 (0–9)**
- Pixel values: **0–255** before normalization

In this assignment, the MNIST dataset is downloaded using **KaggleHub**.

Dataset source:

`hojjatk/mnist-dataset`

---

## Technologies and Libraries Used

- Python
- NumPy
- Matplotlib
- Scikit-learn
- KaggleHub
- MLxtend

### Libraries

```python
import kagglehub
import os
import numpy as np
import matplotlib.pyplot as plt

from mlxtend.data import loadlocal_mnist
from sklearn.model_selection import train_test_split
