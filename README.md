# Vishakha_Project2
#HANDWRITTEN DIGIT RECOGNIZER
OVERVIEW

This project builds a Convolutional Neural Network (CNN) using TensorFlow/Keras to recognize handwritten digits (0–9) from the MNIST dataset. The model learns from thousands of labeled images and predicts digits from new handwritten samples.

STEPS

Load the MNIST dataset from TensorFlow/Keras.

Preprocess images (normalize & reshape).

Build a CNN model with Conv2D, MaxPooling2D, Flatten, Dense layers.

Compile and train the model.

Evaluate accuracy and loss on the test set.

Predict unseen digits and display results.

📂 Dataset

Source: MNIST (built into TensorFlow)

Image Size: 28×28 grayscale

Labels: Digits 0–9

📊 Results

Accuracy: ~98% on test data

Example:

Input Image → Predicted Digit: 7

📦 Requirements

Python 3.x

TensorFlow

NumPy

Matplotlib (optional for visualization)
