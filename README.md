# Iris Flower Classification Using Random Forest

A machine learning project that classifies Iris flowers into three species using the Random Forest algorithm.

## Project Overview

This project demonstrates a complete machine learning workflow using the Iris dataset from Scikit-learn. The model classifies flowers based on four physical measurements:

* Sepal length
* Sepal width
* Petal length
* Petal width

The project includes data exploration, dataset splitting, model training, prediction, evaluation, visualization, and parameter experimentation.

## Dataset

The Iris dataset contains:

* **150 samples**
* **4 numerical features**
* **3 classes:** Setosa, Versicolor, Virginica

The dataset was split into **80% training data** and **20% testing data**.

## Model

**Algorithm:** Random Forest Classifier
**Number of trees:** 100
**Random state:** 42

## Results

The model achieved:

* **Training Accuracy:** 100%
* **Testing Accuracy:** 90%

The project also includes a confusion matrix and feature-importance analysis. Petal width and petal length were the two most important features in the trained model.

A parameter experiment was also performed using 10, 50, 100, and 200 trees to examine the effect of `n_estimators` on testing accuracy.

## Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Random Forest
* Google Colab

## Notebook

The complete implementation is available in [`Iris_Random_Forest.ipynb`](Iris_Random_Forest.ipynb).

[Open in Google Colab](https://colab.research.google.com/drive/1fl8gTi8OGE9n4v8qiQcNZrF5AS05aq6_?usp=sharing)
