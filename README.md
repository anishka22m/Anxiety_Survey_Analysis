# 🧠 Stress & Anxiety Prediction from Mental Health Survey Data

> **Topic:** Machine Learning-Based Analysis and Prediction of Mental Stress & Anxiety  
> **Author:** Anishka Verma
> **Year:** 2024

## 📘 Overview

This repository contains the complete notebook-based workflow for predicting and analyzing **stress and anxiety levels** using a real-world mental health survey dataset. It is structured in two main Jupyter Notebooks:

- 📊 `AnalysisAndVisualization_AnxietyStressLevels_Survey.ipynb` – Exploratory Data Analysis (EDA), cleaning, feature understanding.
- 🤖 `ModelBuilding_AnxietyStressLevels_Survey.ipynb` – Model development, training, evaluation.

---

## 🧾 Table of Contents

1. [Project Objectives](#project-objectives)
2. [Dataset Overview](#dataset-overview)
3. [EDA Highlights](#eda-highlights)
4. [Modeling Approach](#modeling-approach)
5. [Key Findings](#key-findings)
6. [Technologies Used](#technologies-used)
7. [Usage](#usage)
8. [References](#references)

---

## 🎯 Project Objectives

- Understand the relationship between **daily habits**, **demographics**, and **mental health conditions**.
- Use ML techniques to predict whether a person is likely to experience:
  - **Stress**
  - **Anxiety**
- Build a reproducible ML pipeline using Python.

---

## 🧩 Dataset Overview

- 📚 Source: Created the Survey and circulated for real life responses 
- 🎯 Target Variables:
  - `Stress Level`
  - `Anxiety Level`
- 🧠 Features include:
  - Sleep duration
  - Social life
  - Exercise
  - Screen time
  - Academic pressure
  - Diet
  - Gender and age
- 👤 Total entries: 103

---

## 📊 EDA Highlights

- **Correlation analysis** reveals strong inverse relationship between:
  - Sleep vs. Stress
  - Physical Activity vs. Anxiety
- **Distribution plots** show:
  - Higher stress among females and students with low physical activity.
  - Poor diet and screen addiction link to high anxiety levels.
- **Outlier handling** and **missing value imputation** performed.

---

## 🤖 Modeling Approach

| Step | Description |
|------|-------------|
| 1. | Preprocessing – Label encoding, feature scaling |
| 2. | Data Split – Train-test (e.g., 80-20) |
| 3. | Models – Logistic Regression, Decision Tree, Random Forest, KNN |
| 4. | Evaluation – Accuracy, Confusion Matrix, Classification Report |
| 5. | Final Selection – Best-performing model based on F1-score |

📌 Additional Notes:
- Hyperparameter tuning performed using GridSearchCV.
- Random Forest gave highest balanced accuracy across classes.

---

## 📈 Key Findings

- Students with <6 hrs of sleep and high screen time (>6 hrs) showed ~80% likelihood of being stressed or anxious.
- Physical exercise and a structured routine are the strongest **protective factors**.
- Social support correlates inversely with stress levels.

---

## 💻 Technologies Used

- Language: **Python 3.10+**
- Libraries:
  - `pandas`, `numpy`, `matplotlib`, `seaborn` – EDA
  - `scikit-learn` – Model building
- Tools:
  - Jupyter Notebooks

---

