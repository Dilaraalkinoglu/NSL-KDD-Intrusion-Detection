# Deep Learning Based Intrusion Detection System

This repository contains implementations of deep learning models for **Network Intrusion Detection Systems (IDS)** using the NSL-KDD dataset.

This project was developed as part of the **Generative Artificial Intelligence ** course.

The project consists of two main assignments:

1. **Attack Detection using Deep Learning**
2. **Anomaly Detection using Variational Autoencoder (VAE)**

---

## Dataset
https://www.kaggle.com/datasets/hassan06/nslkdd
The models are trained and evaluated using the **NSL-KDD dataset**, which is commonly used for evaluating intrusion detection systems.

The dataset includes labeled network traffic records categorized as:

* Normal traffic
* Various attack types

---

## Assignment 1 – Deep Learning Based Attack Detection

In this task, two deep learning architectures are implemented and compared.

### CNN Model

A **Convolutional Neural Network (CNN)** is trained to classify network traffic as normal or attack.

### AE-CNN Hybrid Model

A hybrid architecture combining:

* **Autoencoder (AE)** for feature extraction
* **CNN** for classification

The **encoder part of the Autoencoder** is used to extract features which are then given as input to the CNN classifier.

### Evaluation Metrics

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

### Training Analysis

Training process is analyzed with the following graphs:

* Training Loss
* Validation Loss
* Training Accuracy
* Validation Accuracy

Finally, the performance of **CNN and AE-CNN models** is compared and discussed.

---

## Assignment 2 – VAE Based Anomaly Detection

In this assignment, a **Variational Autoencoder (VAE)** is used for anomaly detection.

The model learns patterns of **normal network traffic** and identifies anomalies based on **reconstruction error**.

### Evaluation Metrics

* ROC-AUC
* Precision
* Recall
* F1-score
* False Positive Rate (FPR)

### Additional Analysis

The following analyses are included:

* Reconstruction Error Distribution
* Anomaly Threshold Selection
* ROC Curve

---
---

## Technologies Used

* Python
* TensorFlow / PyTorch
* NumPy
* Pandas
---
## Authors

* **Emirhan Kalkan**
* **Dilara Alkınoğlu**

Course: **Üretken Yapay Zeka (Generative Artificial Intelligence)**
Project: **Deep Learning Based Intrusion Detection using NSL-KDD Dataset**

