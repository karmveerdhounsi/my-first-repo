# Diabetes Prediction Using K-Nearest Neighbors (KNN)

This repository contains the implementation and findings of a machine learning model using the K-Nearest Neighbors (KNN) algorithm to predict diabetes based on medical attributes. This project was presented as a seminar by **Karmveer Singh** (Roll No. 24MA60R03) at **Indian Institute of Technology Kharagpur**.

## 📌 Project Overview

Diabetes is a growing global health concern, affecting over 537 million adults worldwide. Early detection is vital for preventing severe health complications and reducing healthcare costs. This project applies the KNN algorithm to predict the likelihood of diabetes using key health indicators.

## 🎯 Objectives

- Improve prediction accuracy for diabetes using the KNN algorithm.
- Identify key health indicators that contribute to diabetes prediction.

## 📊 Dataset Description

The dataset includes medical records of patients with the following attributes:
- Glucose
- Blood Pressure
- Body Mass Index (BMI)
- Insulin Level
- Skin Thickness
- Diabetes Pedigree Function
- Age

## 🔍 Methodology

1. **Data Preprocessing**: Cleaning and preparing the data.
2. **Feature Selection**: Selecting the most relevant attributes.
3. **Model Training**: Training the KNN model.
4. **Hyperparameter Tuning**: Optimizing the value of `k`.
5. **Evaluation**: Using metrics like Accuracy, Precision, Recall, F1 Score, and AUC-ROC.

## 📈 Results

- **Accuracy**: 81.82%
- Balanced performance across **Precision**, **Recall**, and **F1 Score**
- ROC Curve and AUC demonstrate the model’s reliability

## ✅ Strengths of KNN

- Easy to implement and understand
- High accuracy with the right `k` and distance metric
- Non-parametric: makes no assumptions about data distribution

## ⚠️ Limitations of KNN

- Sensitive to irrelevant features and outliers
- Performance drops with high-dimensional data
- Requires careful choice of `k`

## 🔮 Future Work

- Incorporating more features like lifestyle and genetic data
- Real-world clinical testing and validation
- Improving data quality and balance

## 🛠 Technologies Used

- Python
- Scikit-learn
- NumPy, Pandas
- Matplotlib / Seaborn (for visualization)

## 📄 Author

**Karmveer Singh**  
M.Tech, Department of Mathematics and Computing  
IIT Kharagpur  
Roll No: 24MA60R03

---

Feel free to fork this repository, suggest improvements, or raise issues!
