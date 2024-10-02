# Thyroid-Disease-Detection

Welcome to the repository for the research paper "Thyroid Disease Detection using Machine Learning Models", presented at the IEEE Conference, December 2023. This repository contains the code and documentation related to the development and implementation of machine learning models for detecting thyroid illnesses. The models applied include Decision Tree, Random Forest, Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Logistic Regression.

I achieved a highest accuracy of 99% and an F1-score of 0.9879, showcasing the effectiveness of these models in accurately detecting thyroid diseases.

Table of Contents

Introduction
Features
Dataset
Models
Results


## Introduction

Thyroid diseases are common endocrine disorders that can significantly affect metabolism, energy production, and overall health. Early detection is critical for effective treatment and management. This project applies machine learning models to assist in detecting thyroid illnesses based on patient data, improving diagnostic accuracy and aiding healthcare professionals.

The implemented models are optimized for high accuracy and evaluated using metrics like precision, recall, F1-score, and accuracy.

## Features

Machine Learning Models: Implementations of Decision Tree, Random Forest, SVM, KNN, and Logistic Regression.
Performance: Achieved 99% accuracy and an F1-score of 0.9879 for the best-performing model.
Evaluation Metrics: Detailed analysis using accuracy, precision, recall, and F1-score.
Scalability: Models are scalable and can be integrated into healthcare systems for real-time thyroid disease detection.
Dataset

We used a publicly available thyroid disease dataset. The dataset contains the following features:

Patient Information: Age, gender, and medical history.
Thyroid Test Results: TSH, T3, T4, and other relevant biomarkers.
Target Label: Classification into normal or thyroid disease (hypothyroidism or hyperthyroidism).
The dataset is available at [dataset](https://www.kaggle.com/datasets/emmanuelfwerr/thyroid-disease-data) or can be uploaded by the user.

## Models

The following machine learning models were implemented:

Decision Tree
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Logistic Regression
Each model was tuned and evaluated using cross-validation to ensure optimal performance. The best-performing model was the Random Forest, achieving the highest accuracy and F1-score.


## Results
The following results were achieved during the evaluation of the models:

Best Model: Random Forest
Accuracy: 99%
F1-Score: 0.9879
Precision: 0.98
Recall: 0.99
The Random Forest model performed the best, closely followed by Decision Tree and SVM, 98%, and 95% respectively. 
