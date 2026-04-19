# Breast Cancer Classification using Machine Learning Algorithms

Machine learning project for classifying breast cancer tumors as malignant or benign using multiple supervised algorithms.

## Introduction

This project focuses on applying supervised machine learning techniques to classify breast cancer tumors as malignant or benign. The dataset used in this project is provided by the scikit-learn library.

## Objective

The objective of this project is to build and evaluate multiple classification models to accurately predict tumor diagnosis. It also aims to compare the performance of different algorithms and understand the impact of preprocessing techniques such as feature scaling.

## Dataset Description

The breast cancer dataset is loaded from the sklearn library. It contains 569 samples with 30 numerical features and 1 target variable. The target variable represents the diagnosis where 0 indicates malignant and 1 indicates benign.

## Preprocessing

The dataset was checked for missing values and none were found. A boxplot was used to visualize the distribution of features and identify potential outliers. Outliers were not removed as they represent valid medical observations. Feature scaling was applied using StandardScaler to normalize the data and improve model performance.

## Models Used

The following classification algorithms were used in this project:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine
* k Nearest Neighbors

## Model Evaluation

The models were evaluated using accuracy, precision, recall, and F1 score. These metrics helped in comparing the performance of each algorithm and selecting the most effective model.

## Results

Support Vector Machine achieved the highest accuracy among all models, making it the best performing algorithm for this dataset. Decision Tree and k Nearest Neighbors showed comparatively lower accuracy.

## Conclusion

This project demonstrates the importance of preprocessing, model selection, and evaluation in machine learning. It highlights how different algorithms perform on the same dataset and shows that advanced models like Support Vector Machine and Random Forest can provide better results for classification tasks.

## How to Run
Clone the repository
Open the notebook in Jupyter
Run all cells step by step

## Explanation Video

A detailed explanation video is provided below. Please refer to it to understand the project workflow and results
