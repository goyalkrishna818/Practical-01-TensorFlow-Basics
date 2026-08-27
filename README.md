# Practical-01-TensorFlow-Basics

# Practical 2: Binary Classification Using Deep Neural Networks with TensorFlow

## 1. Title
Constructing a Deep Neural Network for Binary Classification Using TensorFlow and Keras.

## 2. Aim of Project
To design, train, and evaluate a fully connected Deep Neural Network (DNN) for solving a binary medical diagnosis classification problem using standard deep learning workflows.

## 3. Dataset Resource
* **Dataset:** Breast Cancer Wisconsin (Diagnostic) Dataset
* **Source:** UCI Machine Learning Repository / Kaggle / Scikit-learn Built-in
* **Dimensions:** 569 instances, 30 continuous numerical features, 2 output classes (Malignant / Benign).

## 4. Outcome Report
* **Performance Summary:** The baseline DNN achieved **98.25% Test Accuracy** with an **F1-Score of 0.98**.
* **Visuals:** Epoch-wise loss and accuracy curves showed convergence around epoch 35 without significant overfitting.
* **Ablation Findings:** 
  * Adam optimizer converged significantly faster than standard SGD.
  * ReLU and Tanh hidden activations outperformed Sigmoid due to vanishing gradient suppression.
  * A 2-hidden layer topology (32 -> 16) provided the optimal trade-off between parameter efficiency and test generalization.

### Author Details
Name: Krishna Goyal
Email: krishnagoyal.btech2024@spsu.ac.in
