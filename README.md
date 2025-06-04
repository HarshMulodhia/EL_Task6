# EL_Task6

# K-Nearest Neighbors Classification on the Iris Dataset

This project demonstrates how to use the K-Nearest Neighbors (KNN) algorithm for classification using the classic Iris flower dataset. It includes data preprocessing, model training, evaluation, and visualization of decision boundaries.

## 🔍 Project Objectives

1. Load and preprocess a classification dataset.
2. Normalize feature values.
3. Train a `KNeighborsClassifier` from `sklearn`.
4. Experiment with different values of `K`.
5. Evaluate the model using accuracy and confusion matrix.
6. Visualize decision boundaries using PCA.

## 📁 Dataset

The dataset used is **Iris.csv**, which includes 150 samples of iris flowers across three species:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

Each sample has the following features:
- SepalLengthCm
- SepalWidthCm
- PetalLengthCm
- PetalWidthCm

## 📊 Output
The script performs the following:

- Splits the dataset into training and testing sets.

- Normalizes the feature values using Min-max Scaling.

- Trains and evaluates a KNN model for multiple values of K.

- Plots Accuracy vs K.

- Displays a confusion matrix for the best-performing model.

- Uses PCA to reduce dimensions and plot decision boundaries.

## 📷 Sample Visualizations
- Accuracy vs. Number of Neighbors (K)

- Confusion Matrix

- 2D Decision Boundaries from PCA projection
