# Credit-Card-Fraud-Detection-using-Quantum-Machine-Learning
Goal:  To build a smart fraud detection system that can:  Identify fraudulent transactions from normal ones  Compare classical machine learning models vs quantum machine learning models (QSVC / VQC)  Demonstrate how quantum computing may improve performance on complex data patterns





Quantum Machine Learning — Fraud Detection
Overview

This project implements a Quantum Support Vector Classifier (QSVC) using Qiskit Machine Learning to detect fraudulent transactions.
It compares quantum models with classical models like Logistic Regression, SVM, and Random Forest.

Dataset

Credit Card Fraud Detection Dataset (Kaggle)

Features: V1–V28, Amount

Target: Class (0 = Normal, 1 = Fraud)

Features

Quantum Feature Map: ZZFeatureMap

Quantum Kernel: FidelityQuantumKernel

Classical ML baseline for comparison

Evaluation: Accuracy, Precision, Recall, F1-score

Usage

Install dependencies:

pip install qiskit qiskit-machine-learning


Run the notebook/script to train and evaluate models.

Author

Pujan Pandey — Quantum Computing & Machine Learning Enthusiast
