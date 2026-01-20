# 🎓 AI Scholarship Eligibility Prediction

This project presents a **machine learning–based system** that predicts whether a university student is eligible for internal scholarships at **Universiti Teknologi PETRONAS (UTP)**.

The system was developed to support **faster, more consistent, and data-driven scholarship screening**, reducing reliance on manual evaluation.

---

## 📌 Overview
Scholarship applications at UTP are traditionally reviewed manually, which can be time-consuming and inconsistent.  
This project explores how **supervised learning models** can assist in predicting eligibility based on student data such as academic performance, financial background, and extracurricular involvement.

---

## 🤖 Models Implemented
- **Logistic Regression** – probabilistic, interpretable classification  
- **Decision Tree** – rule-based model reflecting real eligibility criteria  

Model performance was evaluated using accuracy, precision, recall, and F1-score.

---

## 🧠 Data & Features
The dataset consists of a combination of **real survey responses and synthetic data**, including:
- CGPA  
- Household income  
- Disciplinary record  
- SPM results  
- Extracurricular involvement  
- Existing financial aid status  

Eligibility labels were generated using **rule-based scholarship criteria**.

---

## 🖥️ System Output
A simple **Gradio interface** allows users to:
- Enter student information  
- Select scholarship type (TAZU or YUTP)  
- Instantly receive an eligibility prediction with explanation  

---

## 🛠️ Tools & Technologies
- Python  
- Scikit-learn  
- Logistic Regression & Decision Tree  
- Gradio  

---

## 🚀 Future Work
- Increase dataset size and diversity  
- Apply cross-validation to reduce overfitting  
- Integrate fairness and bias evaluation  
- Deploy as a full decision-support system

---

Developed as part of an **Artificial Intelligence coursework project at UTP**.
