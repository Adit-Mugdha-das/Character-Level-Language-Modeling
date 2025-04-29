# Dinosaur Island - Character-Level Language Modeling

This repository contains the programming assignment from **Week 1** of **Course 5: Sequence Models** in the [Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning) by Andrew Ng on Coursera.

## Overview

In this assignment, a character-level language model is built using a simple Recurrent Neural Network (RNN). The model is trained on a dataset of dinosaur names and learns to generate new, realistic-sounding names by predicting one character at a time.

This exercise reinforces important concepts including:
- One-hot encoding of characters
- RNN forward and backward propagation
- Sampling sequences from a trained model
- Gradient clipping to stabilize training
- Loss computation and parameter updates

## Contents

- `rnn_utils.py` – Helper functions for data preprocessing and initialization
- `rnn_forward()` – Performs forward propagation through the RNN
- `rnn_backward()` – Computes gradients through backpropagation
- `clip()` – Applies gradient clipping
- `sample()` – Generates new dinosaur names based on the model’s learned parameters
- `optimize()` – Executes one step of optimization (forward + backward + update)
- `model()` – Trains the RNN and periodically samples generated names

## Technologies Used

- Python 3
- NumPy

High-level deep learning libraries such as TensorFlow or PyTorch are not used. The model is built entirely with NumPy for educational purposes.

## Course Information

- Course: Sequence Models (Course 5 of 5)
- Specialization: Deep Learning Specialization
- Instructor: Andrew Ng
- Platform: Coursera
- Institution: DeepLearning.AI

## License

This repository is based on educational content provided by DeepLearning.AI through Coursera. It is intended solely for personal and academic use and should not be used for commercial purposes.
