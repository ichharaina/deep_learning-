# Assignment 5 – Comparison of RNN, LSTM and GRU

## Problem Statement

Implement and compare RNN, LSTM, and GRU models for sequence classification, and analyze their performance using appropriate evaluation metrics.

## Objective

To implement different recurrent neural network architectures and compare their performance for sequence classification.

## Dataset

The IMDB Movie Review Dataset is used for binary sentiment classification.

The reviews are classified into:

- Positive
- Negative

## Models Implemented

The following models are implemented and compared:

1. Simple RNN
2. LSTM
3. GRU

## Implementation

The implementation includes:

- Loading the IMDB dataset
- Tokenization and sequence representation
- Padding sequences to a fixed length
- Creating an embedding layer
- Building RNN, LSTM, and GRU models
- Training the models
- Evaluating their performance
- Comparing the results using graphs and evaluation metrics

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Evaluation Metrics

The models are compared using:

- Accuracy
- Precision
- Recall
- F1-Score
- Test Loss

## Result

The performance of RNN, LSTM, and GRU models is compared using the generated evaluation metrics and visualizations.

## Conclusion

RNN, LSTM, and GRU are useful for processing sequential data. Traditional RNNs can face vanishing gradient problems for long sequences, while LSTM and GRU use gating mechanisms to handle long-term dependencies more effectively.

The experimental results provide a comparison of the three architectures for sequence classification.
