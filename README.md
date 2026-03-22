# 🚨 Credit Card Fraud Detection System

## 📌 Overview
This project builds a production-grade fraud detection system using machine learning, focusing on real-world financial decision-making rather than just model accuracy.

---

## 🎯 Objective
- Detect fraudulent transactions with high recall  
- Minimize false positives  
- Optimize decision thresholds based on business cost  

---

## 🧠 Key Features
- Handles extreme class imbalance (~0.17% fraud)
- Threshold tuning (not default 0.5)
- Cost-based evaluation
- Explainable AI (SHAP)
- Decision system (Approve / Review / Block)

---

## 📊 Results
- F1 Score (Fraud): ~0.90  
- ROC-AUC: ~0.98  
- Significant reduction in false positives  

---

## ⚙️ Tech Stack
- Python (Pandas, NumPy)
- Scikit-learn
- XGBoost
- SHAP
- Matplotlib / Seaborn

---

## 🏗️ System Flow
Transaction → Model → Probability → Decision Layer  
→ Approve / Review / Block  

---

## 🚀 How to Run
```bash
pip install -r requirements.txt