# Induction Motor Fault Diagnosis using Machine Learning

This project focuses on diagnosing various fault conditions in induction motors using machine learning algorithms applied on time-domain current signature data.

## Assignments Overview

### Assignment 1
- **Algorithm:** K-Nearest Neighbors (K-NN)
- **Tasks:**
  - Manual implementation of K-NN without libraries
  - Data preprocessing into 1000-sample blocks
  - Hold-out and 10-fold cross-validation
  - PCA-based dimensionality reduction
  - Model performance evaluation: Accuracy, Precision, Recall, F1, Sensitivity, Specificity

### Assignment 2
- **Algorithm:** Logistic Regression
- **Tasks:**
  - Binary and multiclass classification (14-class)
  - Data labeling and processing
  - Performance metrics calculation

### Assignment 3
- **Algorithms:** Naive Bayes, Support Vector Machine (SVM)
- **Tasks:**
  - Binary and multiclass classification
  - Evaluation metrics
  - Training and validation accuracy/loss curves

## Dataset Description
- Three-phase current data of loaded induction motors
- Healthy and fault conditions: inner/outer race bearing faults and broken rotor bars
- Sampling: 10 kHz, 1000 samples per channel
- 39 datasets under varying load conditions (100W, 200W, 300W)

## Technologies Used
- Python (NumPy, Pandas, Matplotlib)
- No external ML libraries for core algorithm implementations
- Jupyter Notebook

## Author
- [Your Name]
