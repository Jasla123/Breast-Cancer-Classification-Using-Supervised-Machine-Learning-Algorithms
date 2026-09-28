# Breast-Cancer-Classification-Using-Supervised-Machine-Learning-Algorithms

## Project Overview

This project uses supervised machine learning algorithms to classify breast cancer tumors as malignant or benign using the Breast Cancer dataset available in the Scikit-learn library.

The project implements five classification algorithms and compares their performance using accuracy scores to identify the best-performing model.

## Objective

The objective of this project is to apply supervised learning techniques to a real-world medical dataset and compare different classification algorithms to understand their performance in predicting breast cancer cases.

## Dataset

- Source: Scikit-learn built-in Breast Cancer Wisconsin dataset
- Number of samples: 569
- Number of features: 30 numerical features
- Target classes: Malignant and Benign

Target labels:

- "0" – Malignant
- "1" – Benign

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Project Workflow

1. Loaded the Breast Cancer dataset from Scikit-learn.
2. Converted the features into a Pandas DataFrame.
3. Checked for missing values.
4. Split the dataset into 80% training data and 20% testing data.
5. Applied StandardScaler to scale features for Logistic Regression, SVM, and k-NN.
6. Trained five classification algorithms.
7. Evaluated model performance using accuracy scores.
8. Compared the models to identify the best- and worst-performing algorithms.

## Machine Learning Algorithms

1. Logistic Regression

A classification algorithm that predicts the probability of a sample belonging to a particular class.

2. Decision Tree Classifier

A tree-based algorithm that makes predictions using decision rules based on feature values.

3. Random Forest Classifier

An ensemble algorithm that combines multiple decision trees to improve prediction performance and reduce overfitting.

4. Support Vector Machine (SVM)

An algorithm that finds a decision boundary to separate different classes with the maximum margin.

5. k-Nearest Neighbors (k-NN)

A distance-based algorithm that classifies a sample based on the majority class among its nearest neighbors.

## Model Evaluation

The models were evaluated using Accuracy Score on the test dataset.

The accuracy scores were compared using a table, and the models were sorted from highest to lowest accuracy.

- Best-performing model: Identified based on the highest test accuracy.
- Worst-performing model: Identified based on the lowest test accuracy.

The final results are available in the Jupyter Notebook.

## Key Findings

- The dataset contains no missing values.
- Feature scaling is important for distance-based and scale-sensitive algorithms.
- All five algorithms were trained and evaluated using the same training and testing split.
- Model comparison helps identify differences in classification performance.

## Conclusion

This project demonstrates the application of five supervised machine learning algorithms to breast cancer classification. The models were trained and evaluated using the Scikit-learn Breast Cancer dataset, and their performance was compared using accuracy scores.

The comparison identifies the best- and worst-performing models on the test set. This project also highlights the importance of data preprocessing, feature scaling, and model evaluation in machine learning.

