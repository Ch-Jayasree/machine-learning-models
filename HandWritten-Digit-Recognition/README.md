# Handwritten Digit Recognition

This project implements handwritten digit classification using machine learning algorithms. The goal is to correctly recognize digits (0–9) from image data.

The model is implemented in **Google Colab** using Python and machine learning libraries such as **scikit-learn**.

---

## Problem Statement

Handwritten digit recognition is a classification problem where the model predicts the digit represented in an image. This project trains machine learning models to classify digits from image pixel values.

---

## Dataset

The project uses the **MNIST Handwritten Digit Dataset**, a widely used dataset for image classification tasks.

---

## Algorithms Used

Two machine learning algorithms were implemented and compared:

### K-Nearest Neighbors (KNN)

* Classifies digits based on similarity with nearby data points.
* Uses distance metrics to determine the closest neighbors.
* Simple but effective for small to medium datasets.

### Decision Tree

* Uses a tree-based structure to split data based on feature values.
* Creates decision rules for classification.
* Easy to interpret and visualize.

---

## Libraries Used

* Python
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## Notebook

The implementation is available in the notebook:

```
KNN-DesicionTree_Digits.ipynb
```

The notebook includes:

* Data loading and preprocessing
* Model training
* Model evaluation
* Accuracy comparison between KNN and Decision Tree

---

## Model Evaluation

The models were evaluated using classification accuracy.

Example results (your results may vary depending on parameters):

```
KNN Accuracy: ~99%
Decision Tree Accuracy: ~88%
```

---

## How to Run the Project

1. Open the notebook in **Google Colab**
2. Run the cells sequentially
3. The notebook will train both models and display prediction results.

---

## Project Objective

The purpose of this project is to demonstrate how machine learning algorithms can be used for image classification tasks such as handwritten digit recognition.

---
