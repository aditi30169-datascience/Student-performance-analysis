# Student Performance Analysis & Prediction

## 📌 Project Overview

This project analyzes student academic performance using Exploratory Data Analysis (EDA) and Machine Learning.

The project uses the UCI Student Performance Dataset and focuses on students' mathematics performance.

The project includes both:

- Regression to predict final grade (G3)
- Classification to predict Pass/Fail outcomes

---

## 🎯 Objectives

- Explore student academic performance data
- Analyze relationships between student characteristics, study habits, absences, and grades
- Identify important factors related to academic performance
- Predict final student grades using regression models
- Predict Pass/Fail outcomes using classification models
- Compare different machine learning algorithms using multiple evaluation metrics

---

## 📊 Dataset

**Dataset:** UCI Student Performance Dataset

The dataset contains information about:

- Student demographics
- Family background
- Study habits
- Previous academic grades
- Absences
- Social activities
- Final mathematics grade

The dataset contains **649 student records** collected from two Portuguese schools.

The Mathematics dataset (`student-mat.csv`) is used in this project.

**Dataset source:** UCI Machine Learning Repository — Student Performance Dataset

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### Tools
- Google Colab
- GitHub

---

## 🔍 Exploratory Data Analysis

The following analyses were performed:

- Final grade distribution
- Study time vs academic performance
- Absences vs academic performance
- Correlation analysis
- Correlation heatmap
- Feature relationships

---

## 🤖 Machine Learning Models

### Regression

The following regression models were implemented:

- Linear Regression
- K-Nearest Neighbors (KNN) Regression
- Decision Tree Regression
- Random Forest Regression

### Classification

Students were classified into two categories:

- **Pass:** G3 ≥ 10
- **Fail:** G3 < 10

The following classification models were implemented:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)

---

## 📈 Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score
- Accuracy
- Precision
- Recall
- F1 Score
- Cohen's Kappa
- ROC-AUC
- Confusion Matrix

---

## 🔎 Key Findings

- Previous academic grades, particularly G1 and G2, provided strong predictive information about the final outcome.
- Random Forest achieved **87.34% accuracy** on the classification test set.
- The Random Forest model achieved a **90.00% F1 Score** and **0.7293 Cohen's Kappa**.
- Removing G1 and G2 from the Random Forest model reduced accuracy from **87.34% to 68.35%**.
- Model performance varied across different machine learning algorithms.

---

## ⚠️ Limitations

- The dataset contains students from two Portuguese schools.
- The dataset contains only 649 records.
- Results may not generalize to students from other schools or countries.
- G1 and G2 provide strong predictive information but may not be available in every prediction scenario.
- The models identify statistical patterns and do not establish causal relationships.
- Model performance can vary depending on the train-test split and preprocessing choices.

---

## 📁 Project Structure

```text
student-performance-analysis/
│
├── student_performance_analysis.ipynb
└── README.md
