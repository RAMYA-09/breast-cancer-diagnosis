# Performing Dimensionality Reduction Techniques for Accurate Breast Cancer Diagnosis
This repository contains the code and resources for a project aimed at improving breast cancer diagnosis using various dimensionality reduction techniques combined with machine learning models.

## Project Overview
Breast cancer is a significant health issue worldwide. Early and accurate diagnosis is crucial for effective treatment. This project applies various dimensionality reduction techniques to improve the performance of machine learning models in diagnosing breast cancer.

## Dataset
The dataset used in this project is the Breast Cancer Wisconsin (Diagnostic) dataset from the sklearn.datasets module. It consists of features computed from breast cancer biopsy samples.

## Data Preprocessing
* Scaling: The data was scaled using MinMaxScaler to normalize the feature values.
* Train-Test Split: The data was split into training and testing sets to evaluate model performance.
* Dimensionality Reduction Techniques
Several dimensionality reduction techniques were applied to the dataset:

1. Principal Component Analysis (PCA)
2. Linear Discriminant Analysis (LDA)
3. Multidimensional Scaling (MDS)

## Model Development
Multiple machine learning models were trained and evaluated:

1. K-Nearest Neighbors (KNN)
2. Support Vector Classifier (SVC)
3. Gradient Boosting Classifier
4. Random Forest Classifier
5. Decision Tree Classifier
6. Logistic Regression
   
## Results
The models were evaluated using various metrics such as confusion matrix, classification report, ROC curve, and AUC score. The results demonstrated the effectiveness of combining dimensionality reduction techniques with machine learning models for accurate breast cancer diagnosis.
