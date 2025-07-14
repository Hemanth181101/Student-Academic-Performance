# 🎓 Student-Academic-Performance

This project uses machine learning techniques to predict and classify student academic performance into three categories: **High (H)**, **Medium (M)**, and **Low (L)**. It leverages behavioral and academic engagement data such as participation, resource usage, and absenteeism from a real-world dataset.

---


## 🧩 Problem Statement

Academic institutions often lack predictive tools to identify students at risk of poor performance. The goal is to build a system that can classify students' academic performance using historical and behavioral data for early intervention and support.

---

## 💡 Proposed Solution

- Classifies students into performance levels (High, Medium, Low)
- Trains multiple machine learning models for comparison
- Includes visual insights (EDA) and an interactive prediction interface
- Enables real-time prediction by entering custom student data

---

## 🛠️ Technologies Used

- **Python 3.9+**
- **Libraries:**
  - `pandas`, `numpy` – Data handling
  - `matplotlib`, `seaborn` – Visualization
  - `sklearn` – Machine learning models and preprocessing
  - `time`, `warnings` – Runtime management

---

## 📂 Dataset Overview

Dataset: `AI-Data.csv`

**Features include:**
- Demographics: Gender, Nationality, Place of Birth, Stage, Grade
- Academic Behavior: RaisedHands, VisitedResources, AnnouncementsView, Discussion
- Engagement: Parent Survey, Satisfaction, Absences
- **Target:** `Class` (H, M, L)

---

## 🤖 Models Implemented

- Decision Tree Classifier
- Random Forest Classifier
- Perceptron (Linear Model)
- Logistic Regression
- Multi-layer Perceptron (Neural Network)

All models are trained, tested, and evaluated using accuracy, precision, recall, and F1-score metrics.

---

## ▶️ How to Run

1. **Clone this repository**  
   ```bash
   git clone https://github.com/your-username/student-performance-classification.git
   cd student-performance-classification
