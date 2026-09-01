# Assignment 2: MLP Classification on Wine Dataset

## Aim

To implement a **Multi-Layer Perceptron (MLP) classifier** on the Wine dataset, evaluate its performance using different train-test split scenarios, and compare two MLP architectures using classification metrics, confusion matrices, loss curves, and 10-fold cross-validation.

---

## Dataset

The **Wine dataset** is a built-in dataset available in Scikit-learn. It contains chemical analysis results of wines belonging to three different classes.

The dataset contains:

- **178 samples**
- **13 features**
- **3 target classes**
- Classes: `0`, `1`, and `2`

The dataset can be loaded directly using:

```python
wine = datasets.load_wine()
