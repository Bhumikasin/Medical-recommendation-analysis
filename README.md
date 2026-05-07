# 🩺 Personalized Medical Recommendation System using Machine Learning

## 📌 Overview
This project is a *Machine Learning based Medical Recommendation System* that predicts possible diseases based on user symptoms and provides basic recommendations.

It helps users understand their health condition quickly by analyzing symptoms using trained ML models.

---

## 🚀 Features
- 🔍 Disease Prediction based on symptoms  
- 🤖 Machine Learning model (trained on medical dataset)  
- 📊 Data preprocessing & feature selection  
- 🧠 Accurate prediction using classification algorithms  
- 💡 Simple and user-friendly interface (Jupyter Notebook)

---

## 🛠️ Tech Stack
- Python 🐍  
- Pandas & NumPy  
- Scikit-learn  
- Jupyter Notebook  

---

## 📂 Dataset
- Dataset contains various symptoms and corresponding diseases  
- Format: CSV file  
- Example symptoms:
  - itching  
  - skin rash  
  - joint pain  
  - stomach pain  

---

## ⚙️ Working Process

### 1️⃣ Data Loading
Dataset is loaded using pandas:
```python
import pandas as pd
dataset = pd.read_csv("Training.csv")
