# Breast Cancer Classification Using a Regularized Feedforward Neural Network (FFNN)

## Overview

This project presents a **Feedforward Neural Network (FFNN)** for classifying breast tumors as **Benign** or **Malignant** using the **Breast Cancer Wisconsin Diagnostic Dataset**. The objective was to design, train, and optimize a deep learning model while analyzing the effects of regularization techniques on model performance.

The project demonstrates how **Batch Normalization**, **Dropout**, and **Early Stopping** improve model generalization and prevent overfitting, resulting in highly accurate predictions.

---

## Objectives

- Develop a Feedforward Neural Network for breast cancer classification.
- Compare baseline and regularized models.
- Analyze different optimizer and loss function combinations.
- Reduce overfitting using regularization techniques.
- Evaluate the model using standard classification metrics.

---

## Model Architecture

- **Input Layer:** 20 Features
- **Hidden Layers:** 5
- **Neurons per Hidden Layer:** 10
- **Activation Function:** ReLU
- **Output Layer:** 1 Neuron
- **Output Activation:** Sigmoid

### Regularization Techniques
- Batch Normalization
- Dropout (0.2)
- Early Stopping

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Dataset

**Breast Cancer Wisconsin Diagnostic Dataset**

The dataset contains extracted features from digitized images of breast cell nuclei.

- Binary Classification
- Classes:
  - Benign (0)
  - Malignant (1)

---

## Experiments Performed

- Baseline FFNN Model
- Optimizer Comparison
  - SGD
  - Adam
- Loss Function Comparison
  - Mean Squared Error (MSE)
  - Binary Cross-Entropy (BCE)
- Baseline vs Regularized Model
- Final Model Evaluation

---

## Performance Evaluation

The final model was evaluated using:

- Accuracy
- Confusion Matrix
- ROC Curve
- AUC Score
- Training & Validation Loss
- Training & Validation Accuracy

### Final Results

| Metric | Value |
|---------|-------|
| Test Accuracy | **100%** |
| Sensitivity | **100%** |
| Specificity | **100%** |
| AUC Score | **1.00** |

---


## Results

The project includes:

- Baseline Model Analysis
- Baseline vs Regularized Comparison
- Final Training Curves
- Confusion Matrix
- ROC Curve
- Probability Distribution

---

## Learning Outcomes

Through this project, I learned:

- Feedforward Neural Networks
- Binary Classification
- Overfitting Analysis
- Model Regularization
- Hyperparameter Tuning
- Performance Evaluation using ROC and Confusion Matrix
- Deep Learning Model Optimization

---

## Future Improvements

- Hyperparameter optimization using Bayesian Optimization.
- Cross-validation for improved robustness.
- Comparison with CNNs and other deep learning architectures.
- Deployment as a web-based diagnostic application.

---

## 👨‍💻 Author

**Srinitya Gargeyi Vadlamani**

B.Tech – Electronics and Communication Engineering (AI & ML)
