# Iris Dataset Understanding and Visualization

## Part 1: Dataset Understanding

## Dataset Overview

The Iris dataset is a classic dataset from the UCI Machine Learning Repository. It is widely used in statistics and machine learning as an introductory dataset for classification tasks. The purpose of this dataset is to classify iris plants into different species based on measurements of their flower parts.

## Purpose of the Dataset

The main purpose of the Iris dataset is to support classification modelling. In this dataset, the target variable is the class of iris plant. A machine learning model can use the flower measurements to predict whether a plant belongs to Iris Setosa, Iris Versicolour, or Iris Virginica.

## Key Features

The dataset contains 150 instances, where each instance represents one iris plant. There are four main input features, all measured in centimetres:

* Sepal length
* Sepal width
* Petal length
* Petal width

These features describe the physical measurements of the iris flower. They are useful because different iris species tend to have different flower dimensions.

## Main Variables

The four feature variables are continuous numerical variables. The target variable is categorical and represents the species of the iris plant. The three classes are:

* Iris Setosa
* Iris Versicolour
* Iris Virginica

Each class contains 50 instances, which means the dataset is balanced across the three species.

## Notable Observations

A notable feature of this dataset is that it is simple, clean, and does not contain missing values. This makes it suitable for beginners learning data analysis, classification, and machine learning. Another important observation is that one iris class is linearly separable from the other two, while the remaining two classes are more difficult to separate. This makes the dataset useful for understanding how classification models work and how different features can help distinguish between categories.

Overall, the Iris dataset is a small but valuable dataset for learning how to explore data, understand variables, and prepare for classification-based machine learning tasks.

---

## Part 2: Iris Dataset Visualization

## Visualization Task

For Part 2, I used Python to count the number of samples for each iris flower class and visualized the result using a bar chart. The aim of this visualization was to check the class distribution of the dataset and determine whether the classes are balanced.

## Method

The Iris dataset was loaded using Python in Google Colab. The target class column was used to count how many samples belong to each flower species. After counting the samples, a bar chart was created to show the number of observations for each class.

The visualization focuses on the three iris classes:

* Iris Setosa
* Iris Versicolour
* Iris Virginica

## Visualization Result

The bar chart shows that each iris class has the same number of samples:

* Iris Setosa: 50 samples
* Iris Versicolour: 50 samples
* Iris Virginica: 50 samples

This result confirms that the dataset is balanced because all three classes contain an equal number of observations.

## Visualization Insight

The Iris dataset is balanced, with 50 samples in each of the three flower classes. This is useful for classification tasks because the model is not biased toward one class with more samples. A balanced dataset helps make model training and evaluation fairer across all classes.

The bar chart also makes the class distribution easy to understand at a glance. Instead of only reading numbers in a table, the visualization clearly shows that all three flower classes have equal representation in the dataset.

## Files Included

This repository includes:

* README.md
* iris_visualization.ipynb
* iris_class_distribution.png

## Conclusion

Through this activity, I learned how to use Python to explore and visualize a dataset. I also learned that checking class balance is an important step before using a dataset for machine learning classification. The Iris dataset is suitable for beginner-level data analysis and classification practice because it is clean, simple, and balanced.
