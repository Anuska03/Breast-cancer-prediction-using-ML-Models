# Breast Cancer Prediction using Machine Learning

## Overview

This project focuses on predicting breast cancer using supervised machine learning classification techniques. The goal is to classify tumors as **malignant** or **benign** based on diagnostic features by training and comparing multiple machine learning models.

The repository demonstrates an end-to-end ML workflow including data preprocessing, model training, evaluation, and performance comparison.

The project implements **K-Nearest Neighbors (KNN)**, **Support Vector Machine (SVM)**, and **Random Forest** classifiers and compares their accuracies to identify the most effective approach for this medical classification task.

## Problem Statement

Breast cancer is one of the most common cancers worldwide, and early diagnosis plays a critical role in improving survival rates. Using machine learning models to assist in classification can support faster and more reliable decision-making.

This project aims to:
- Train multiple ML models on diagnostic breast cancer data
- Evaluate and compare their performance
- Understand the strengths and limitations of different algorithms

## Dataset

The dataset contains numerical features derived from breast cancer diagnostic measurements. Each sample is labeled as either **malignant** or **benign**.

**Key characteristics:**
- Structured tabular data
- Binary classification problem
- Features require scaling for optimal model performance

## Machine Learning Models Used

### 1. K-Nearest Neighbors (KNN)
- Distance-based classifier
- Sensitive to feature scaling
- Useful as a baseline model

### 2. Support Vector Machine (SVM)
- Effective for high-dimensional data
- Uses a decision boundary to separate classes
- Strong performance on medical classification tasks

### 3. Random Forest
- Ensemble learning method using decision trees
- Handles non-linearity and feature interactions well
- Provides robust and stable predictions

## Methodology

### Data Loading
- Import dataset and required libraries

### Data Preprocessing
- Handling missing values (if any)
- Feature scaling using standardization
- Train-test split

### Model Training
- Train KNN, SVM, and Random Forest models
- Tune key hyperparameters where applicable

### Evaluation
- Measure model accuracy
- Compare performance across models
- Analyze results to determine the best-performing classifier

## Results

The trained models are evaluated based on their classification accuracy on the test dataset. A comparative analysis highlights differences in performance between KNN, SVM, and Random Forest, helping identify which model generalizes best for breast cancer prediction.

The results demonstrate how ensemble and margin-based methods often outperform simpler distance-based classifiers on structured medical datasets.

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Google Colab


