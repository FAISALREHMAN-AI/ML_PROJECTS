# Credit Card Fraud Detection System

## 📌 Project Overview
This project implements an end-to-end Machine Learning pipeline to identify fraudulent credit card transactions. With only 0.17% of the dataset representing fraud, the system focuses on handling extreme class imbalance using SMOTE (Synthetic Minority Over-sampling Technique).

## 🛠️ Technical Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-Learn, Imbalanced-Learn (SMOTE)

## 📊 Strategic Business Insights
* **Logistic Regression:** Achieved high recall but generated significant false alarms (customer friction).
* **Random Forest:** The optimal model, balancing a 92% fraud recall with 81% precision to ensure secure yet seamless user experiences.

## 🚀 Future Enhancements
* Implementing Isolation Forests for unsupervised anomaly detection.
* Deployment via FastAPI microservices for sub-10ms latency.