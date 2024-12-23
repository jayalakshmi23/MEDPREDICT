# MEDPREDICT

## 🚀 Overview
The **Hospital Readmission Prediction System** - MEDPREDCIT is a cutting-edge project designed to leverage advanced Large Language Models (LLMs) to predict hospital readmissions within 30 days. Developed as part of the **DATA 298B Capstone Project** at **San Jose State University**, this system empowers healthcare professionals with actionable insights, enabling better patient care and efficient resource utilization.

---

## 🩺 Objective
The primary goal is to reduce hospital readmissions by building a scalable, accurate, and real-time prediction system using the **MIMIC-III dataset**. The system integrates with healthcare IT systems to provide healthcare providers with insights to:
- Identify high-risk patients.
- Personalize care plans.
- Optimize hospital resources.

---

## 📊 Dataset
The project utilizes the publicly available **MIMIC-III (Medical Information Mart for Intensive Care)** dataset, which includes:
- Patient demographics
- Admission and discharge information
- Medical history and diagnoses
- Clinical notes and lab results

---

## 💡 Key Features
### **Advanced Predictive Models**
- ClinicalBERT
- PubMedBERT
- Clinical BigBird
- GPT-4 Turbo
- Clinical XLNet

### **Performance Metrics**
- Accuracy: **85%+**
- Precision, Recall, F1-Score: **Above industry standards**

### **Secure & Scalable Architecture**
- Built using **Python**, **FastAPI**, and **React**.
- Cloud storage on **AWS S3**, ensuring **HIPAA compliance**.

---

## 🛠 Tech Stack
- **Backend**: Python, FastAPI
- **Frontend**: React
- **Cloud**: AWS (S3, EC2)
- **Libraries**: PyTorch, Hugging Face Transformers, Med7
- **Data Analysis**: Pandas, NumPy, Scikit-learn

---

## ⚙️ How It Works
### **Data Preprocessing**
1. Cleaned, tokenized, and normalized patient data.
2. Feature engineering to identify key predictors of readmission.

### **Model Training**
1. Trained multiple LLMs on structured and unstructured data.
2. Fine-tuned for maximum predictive accuracy.

### **Evaluation**
- Assessed model performance using metrics like accuracy, precision, recall, and F1-score.

### **Deployment**
- Real-time prediction system integrated with a React-based user interface.

---

## 🎯 Outcomes
- **Proactive Healthcare**: Early identification of high-risk patients.
- **Optimized Resources**: Improved allocation of hospital resources.
- **Enhanced Patient Care**: Reduced readmission rates and better health outcomes.

---

## 🔧 Installation
### **Prerequisites**
- Python 3.9+
- Node.js
- AWS account

### **Steps**
1. Clone the repository:
   ```bash
   git clone https://github.com/jayalakshmi23/MEDPREDICT.git
   cd MEDPREDICT
2. pip install -r requirements.txt
3. cd frontend
npm install
4. uvicorn app.main:app --reload
5. npm start

## 🙌 Acknowledgments
- **Team Members**: Jaya Lakshmi Gunji, Naveen Yadav Gongati, Neha Dabeeru, Priyanka Akula, Somna Sattoor
- **Mentor**: Simon Shim
- **Dataset**: MIMIC-III Database

   
   
