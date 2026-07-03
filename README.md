
# Machine Learning-based Intrusion Detection for Detecting Internet of Things Network Attacks

## Overview

This project presents a Machine Learning-based Intrusion Detection System (IDS) for identifying malicious network traffic in Internet of Things (IoT) environments. The system leverages multiple supervised machine learning algorithms to classify normal and attack traffic using the UNSW-NB15 dataset.

The objective is to improve IoT network security by accurately detecting various cyberattacks while reducing false alarms through effective preprocessing and feature reduction techniques.

---

## Project Objectives

- Develop an Intrusion Detection System (IDS) for IoT networks.
- Preprocess the UNSW-NB15 dataset using Min-Max Normalization.
- Reduce feature dimensionality using Principal Component Analysis (PCA).
- Train and evaluate multiple Machine Learning algorithms.
- Compare model performance using standard evaluation metrics.

---

## Dataset

**Dataset:** UNSW-NB15

The dataset contains normal network traffic and multiple categories of modern cyberattacks, making it suitable for evaluating intrusion detection models in IoT environments.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- CatBoost
- Matplotlib
- Seaborn

---

## Machine Learning Pipeline

1. Data Collection
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
   - Missing value analysis
   - Min-Max Normalization
   - Label Encoding
4. Principal Component Analysis (PCA)
5. Model Training
6. Performance Evaluation

---

## Machine Learning Models

The following models were implemented and compared:

- XGBoost
- CatBoost
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Quadratic Discriminant Analysis (QDA)
- Naïve Bayes

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Cohen's Kappa
- Matthews Correlation Coefficient (MCC)

---

## Results

The experimental results indicate that ensemble models such as **CatBoost** and **XGBoost** achieved superior performance compared to the other classifiers.

Performance was analysed using:

- Confusion Matrix
- Classification Report
- Feature Importance
- Calibration Curve
- ROC-AUC
- PCA Explained Variance

---


## Project Outcomes

- Built an IoT Intrusion Detection System using Machine Learning.
- Applied dimensionality reduction using PCA.
- Compared six different supervised learning algorithms.
- Analysed the strengths and limitations of each classifier.

---

## Future Work

Future improvements may include:

- Deep Learning-based IDS
- Real-time intrusion detection
- Federated Learning for IoT security
- Explainable AI (XAI)
- Edge deployment for resource-constrained IoT devices

---
