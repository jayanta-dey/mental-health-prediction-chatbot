# Student Mental Health Prediction System with Conversational AI

A comprehensive **machine learning–driven predictive framework** integrated with a
**conversational AI chatbot** for early mental health triage and risk assessment of
university students.

---

## Project Overview
Mental health challenges such as **stress, anxiety, and depression** are increasingly
prevalent among university students. This project proposes an **AI-assisted early screening
system** that leverages machine learning models and a conversational chatbot interface
to provide confidential, accessible, and real-time mental health risk assessments.

The system utilizes **clinically validated psychological instruments**:
- **PHQ-9** — Depression assessment  
- **GAD-7** — Anxiety assessment  
- **PSS-10** — Stress assessment  

The primary goal is to support **early intervention and awareness**, not diagnosis.

---

## Core Capabilities
- Separate predictive models for **Stress, Anxiety, and Depression**
- Robust **data preprocessing and exploratory data analysis (EDA)**
- Multi-model evaluation (Regression & Classification)
- RESTful backend API for real-time inference
- Conversational AI chatbot for user interaction
- Crisis keyword detection for safety awareness
- Therapy technique retrieval using **RAG (Retrieval-Augmented Generation)**

---

## Dataset Description
- **Total Samples:** 2029 university students  
- **Feature Set:**  
  - Demographic attributes  
  - Standardized psychological assessment scores  
- **Target Variables:**  
  - Stress level (PSS-10)  
  - Anxiety level (GAD-7)  
  - Depression level (PHQ-9)  

> ⚠️ The dataset is used strictly for **academic and research purposes** and follows
ethical data-handling principles.

---

## ⚙️ Technology Stack
- **Programming Language:** Python  
- **Data Analysis:** Pandas, NumPy  
- **Machine Learning:** Scikit-learn  
- **Visualization:** Matplotlib, Seaborn  
- **Backend API:** Flask / FastAPI  
- **Frontend:** HTML, CSS  
- **Model Serialization:** Pickle  

---

##  System Architecture
The system follows a modular **ML–AI hybrid architecture**:

1. **Data Preprocessing & Exploratory Data Analysis**
2. **Model Training, Evaluation, and Selection**
3. **Model Deployment via REST API**
4. **Conversational AI Chatbot Interface**
5. **User Feedback and Continuous Improvement Loop**

This design ensures scalability, interpretability, and ease of deployment.

---

## Model Performance Summary
- **Linear & Ridge Regression** achieved near-perfect R² scores for score prediction
- **Logistic Regression** employed for categorical risk-level classification
- **Gradient Boosting & Random Forest** evaluated for comparative analysis
- Separate models trained for each mental health dimension to ensure independence
  and interpretability

---

## User Interface
- Web-based input form for demographic and assessment responses
- Result page displaying **mental health risk categories** (Low / Moderate / High)
- Supportive feedback and guidance based on predicted risk level
- Designed for simplicity, confidentiality, and ease of use

---

##  Research Contribution
This repository accompanies a full academic research paper detailing:
- Dataset analysis
- Feature engineering
- Model evaluation
- System integration


## 📄 Research Paper

The complete research paper describing the methodology, dataset analysis,
model evaluation, and system architecture is available here:

📘 [Download PDF](paper/Mental%20Health%20Prediction.pdf)


---

## Ethical Disclaimer
This system **does NOT provide medical diagnosis or treatment**.

It is intended solely for:
- Academic research
- Early mental health screening
- Awareness and support facilitation

Individuals experiencing distress or crisis are strongly encouraged to seek
professional mental health services.

---

##  Author
**Jayanta Dey**  
Department of Electrical and Computer Engineering  
North South University  

---

##  License
This project is released under the **MIT License**, allowing academic and research use
with proper attribution.
