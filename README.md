Lightweight Anomaly-Based Intrusion Detection System for UAV Networks Using Hybrid Deep Learning

Overview
This repository presents an anomaly-based Intrusion Detection System (IDS) designed for UAV (Unmanned Aerial Vehicle) networks. The system is built using a hybrid deep learning and machine learning framework to detect and classify cyber-attacks in real time under resource-constrained environments.
The work is evaluated using the CSE-CIC-IDS2019 dataset, which contains realistic network traffic including benign flows and multiple attack types such as DoS, DDoS, brute force, and infiltration attacks.

Methodology
The proposed pipeline consists of the following stages:
Data preprocessing and cleaning
Handling missing and infinite values
Feature scaling using standardization
Label encoding of categorical features
Class balancing using SMOTE
Model training and evaluation

Models Implemented
The following models were evaluated for performance comparison:
Linear Discriminant Analysis (LDA)
K-Nearest Neighbors (KNN)
Multi-Layer Perceptron (MLP)
XGBoost (Gradient Boosting)
CNN-LSTM (Hybrid Deep Learning Model)

Experimental Results
Model	Accuracy
XGBoost	99.38%
MLP	98.45%
CNN-LSTM	98.23%
KNN	95.56%
LDA	69.90%
XGBoost achieved the highest performance, while CNN-LSTM demonstrated strong capability in learning temporal patterns in network traffic.
Dataset

CSE-CIC-IDS2019
Canadian Institute for Cybersecurity
A real-world network intrusion dataset containing labeled attack scenarios.

Tools and Technologies
Python
Pandas
NumPy
Scikit-learn
TensorFlow / Keras
XGBoost
Imbalanced-learn (SMOTE)
Google Colab

Key Contribution

This work focuses on designing a lightweight and adaptive IDS framework for UAV networks, balancing high detection accuracy with computational efficiency.

Future Work
Federated learning for UAV swarm security
Edge deployment optimization
Real-time UAV flight testing
Lightweight on-device IDS models
Author

Muhammad Shahmeer Razi
Cybersecurity and Machine Learning Research
