# Intrusion Detection System using Dimensionality Reduction and Machine Learning

## Overview
This project presents a comparative study of dimensionality reduction techniques and machine learning/deep learning classifiers for Intrusion Detection Systems (IDS). The main objective is to improve intrusion detection performance while reducing feature dimensionality and computational complexity.

The project evaluates the impact of different dimensionality reduction methods on various classifiers using multiple cybersecurity datasets.

---

## Datasets Used

The following benchmark intrusion detection datasets were used:

- NSL-KDD
- UNSW-NB15
- CIC-IDS-2017

---

## Dimensionality Reduction Techniques

The following feature reduction methods were implemented and compared:

1. Principal Component Analysis (PCA)
2. Autoencoder-based Feature Reduction
3. Mutual Information Feature Selection
4. Raw Features (No Reduction)

---

## Machine Learning Models

### Deep Learning Model
- LSTM (Long Short-Term Memory)

### Traditional Machine Learning Models
- Decision Tree (J48 equivalent)
- PART Rule-based Classifier
- Random Forest
- Naive Bayes

---

## Features of the Project

- Comparative analysis of dimensionality reduction techniques
- Evaluation on multiple IDS benchmark datasets
- Performance comparison of deep learning and traditional ML models
- Visualization of accuracy, F1-score, false positive rate, and execution time
- Autoencoder-based non-linear feature extraction
- Reproducible experimental setup

---

## Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- False Positive Rate (FPR)
- Execution Time

---

## Project Workflow

1. Data Loading and Preprocessing
2. Feature Encoding and Scaling
3. Dimensionality Reduction
4. Model Training
5. Prediction and Evaluation
6. Comparative Analysis
7. Visualization of Results

---

## Results

The comparative study showed that:

- Autoencoder improved LSTM performance significantly.
- PCA improved Naive Bayes performance.
- Mutual Information worked effectively with Random Forest.
- Decision Tree models performed well even without dimensionality reduction.

The best-performing configuration varied depending on the dataset and classifier.
