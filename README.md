# 🧠 Breast Cancer Classification & Model Evaluation

## 📌 Overview

This project demonstrates a complete machine learning classification workflow using the **Breast Cancer Wisconsin Diagnostic dataset** available through Scikit-learn.

Two machine learning models were implemented and evaluated:

- Logistic Regression
- Random Forest

The models were evaluated using multiple classification metrics, including Accuracy, Precision, Recall, F1 Score, ROC Curve, and AUC.

---

## 🎯 Objectives

- Load and explore a classification dataset
- Perform exploratory data analysis
- Prepare data for machine learning
- Split the dataset into training and testing sets
- Apply feature scaling
- Train classification models
- Generate a confusion matrix
- Evaluate model performance
- Plot ROC curves
- Calculate AUC
- Analyze feature importance
- Compare different machine learning models

---

## 📊 Dataset

The project uses the **Breast Cancer Wisconsin Diagnostic dataset** provided by Scikit-learn.

### Dataset characteristics

- **569 samples**
- **30 numerical features**
- **2 target classes**
  - Malignant
  - Benign

The dataset contains measurements computed from digitized images of breast mass cell nuclei.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🤖 Machine Learning Models

### 1. Logistic Regression

Logistic Regression was used as the baseline classification model. Since the features have different numerical scales, StandardScaler was applied before training.

### 2. Random Forest

Random Forest was implemented as a second classification model and was also used to analyze feature importance.

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve
- AUC

---

## 📊 Results

### Logistic Regression

| Metric | Score |
|---|---:|
| Accuracy | 98.25% |
| Precision | 98.61% |
| Recall | 98.61% |
| F1 Score | 98.61% |
| AUC | 99.54% |

### Random Forest

| Metric | Score |
|---|---:|
| Accuracy | 95.61% |
| Precision | 95.89% |
| Recall | 97.22% |
| F1 Score | 96.55% |
| AUC | 99.37% |

> These results are based on the held-out test set used in this project.

---

## 🔍 Key Concepts Demonstrated

### Confusion Matrix

The confusion matrix was used to analyze correct and incorrect predictions for both target classes.

### ROC Curve

The ROC curve evaluates the model's ability to distinguish between the two classes across different classification thresholds.

### AUC

The Area Under the ROC Curve summarizes the model's class-separation performance across thresholds.

### Feature Importance

Random Forest feature importance was used to identify features that contributed most to the model's predictions.

---

## 📁 Project Structure

```text
ML-Classification-Evaluation/
│
├── classification_analysis.ipynb
├── requirements.txt
└── README.md
