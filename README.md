# Iris Flower Classification

## Problem Description

The **Iris flower dataset** is one of the most famous datasets in machine learning, often used for classification problems. It consists of data for **three species of iris flowers**: Setosa, Versicolor, and Virginica. The dataset contains **150 samples** with **four features** for each sample:

- **Sepal length**
- **Sepal width**
- **Petal length**
- **Petal width**

### Goal:
The goal is to build a machine learning model that can **classify iris flowers** into one of the three species based on the four features. The model should be trained using the dataset and then evaluated using various performance metrics.

### Dataset Details:
- **Number of Instances**: 150
- **Number of Features**: 4
- **Class Labels**: 3 (Setosa, Versicolor, Virginica)

### Features:
- **Sepal length**: The length of the sepal (in centimeters).
- **Sepal width**: The width of the sepal (in centimeters).
- **Petal length**: The length of the petal (in centimeters).
- **Petal width**: The width of the petal (in centimeters).

### Classes:
- **Setosa**: One species of iris.
- **Versicolor**: Another species of iris.
- **Virginica**: The third species of iris.

## Model Description

In this project, we use the **Random Forest Classifier** to classify the Iris flowers based on their features. The model is trained and evaluated on a hold-out test set. Various visualizations like **Pairplot**, **Feature Importance**, and **Confusion Matrix** are used to analyze the data and model performance.

---

## Steps Involved:
1. **Data Preprocessing**: Load and explore the Iris dataset.
2. **Model Training**: Train a Random Forest Classifier on the training set.
3. **Model Evaluation**: Evaluate the model using accuracy and other performance metrics.
4. **Visualizations**: Generate plots to better understand the data and model performance.
