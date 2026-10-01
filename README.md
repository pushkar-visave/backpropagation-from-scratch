# Backpropagation from Scratch vs Keras

A neural network built manually using NumPy to understand how 
backpropagation works under the hood, then replicated in Keras 
to validate results.

## Problem
Predict a student's salary (LPA) from their CGPA and profile score.

## Network Architecture
Input(2) → Hidden(2) → Output(1)

## What's covered
- Weight and bias initialisation
- Forward propagation
- Backpropagation and gradient descent (manual)
- Training loop with epochs
- Keras equivalent with identical starting weights
- Side-by-side comparison of predictions and loss

## Stack
Python · NumPy · Pandas · TensorFlow/Keras

## Results
Both models trained for 5 epochs with SGD (lr=0.001).
Loss drops from ~26 to ~1.5, confirming the manual 
implementation is correct.
