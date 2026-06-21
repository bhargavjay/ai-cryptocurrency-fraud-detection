# AI Cryptocurrency Fraud Detection System
MSc Data Science Dissertation Project | Federated Learning | XGBoost | SHAP | LIME | Explainable AI

## 📌 Overview

This project develops a privacy-preserving cryptocurrency fraud detection system using Federated Learning (FL) and Explainable Artificial Intelligence (XAI). The objective is to detect fraudulent cryptocurrency transactions in peer-to-peer (P2P) mobile payment systems while preserving user privacy and ensuring model transparency.

The system combines machine learning algorithms, federated learning simulations, and explainability techniques, such as SHAP and LIME, to enhance fraud detection accuracy, interpretability, and scalability.

---

## 🎯 Objectives

* Develop a privacy-preserving fraud detection framework for cryptocurrency transactions.
* Enable collaborative model training without sharing sensitive raw transaction data.
* Implement Federated Learning to support decentralised fraud detection.
* Apply Explainable AI techniques to improve model transparency and trust.
* Detect fraudulent transaction patterns with high accuracy.
* Build a scalable framework adaptable to evolving fraud behaviours.

---

## 📊 Dataset

The project uses a cryptocurrency transaction dataset containing transaction-related information such as:

* Wallet identifiers
* Transaction amounts
* Currency codes
* Transaction fees
* Transaction timestamps
* Mining pool information

The dataset was processed and enhanced through extensive feature engineering to support fraud detection analysis.

---

## ⚙️ Methodology

The project follows a complete machine learning pipeline:

1. Data Collection and Exploration
2. Data Preprocessing
3. Feature Engineering
4. Federated Learning Simulation
5. Machine Learning Model Training
6. Model Evaluation
7. Explainable AI Analysis
8. Fraud Pattern Interpretation

---

## 🔹 Data Preprocessing

Several preprocessing techniques were applied to improve data quality and model performance:

* Missing value handling
* Duplicate record removal
* Outlier detection and treatment
* Data normalization and standardization
* Categorical variable encoding
* Feature scaling

Feature engineering generated additional behavioural indicators including:

* Fee-to-Amount Ratio
* Log Fee Ratio
* Sender Transaction Count
* Receiver Transaction Count
* Transaction Time Delta
* Hour of Transaction
* Day of Week
* Weekend Indicators

---

## 🔹 Federated Learning Framework

A Federated Learning simulation was implemented to mimic multiple decentralized payment platforms.

The dataset was divided into multiple virtual nodes, where each node trained a local machine learning model independently. Model parameters were aggregated into a global model without transferring raw transaction data.

Benefits:

* Improved privacy protection
* Decentralized model training
* Reduced data-sharing risks
* Enhanced scalability

---

## 🔹 Machine Learning Models

Several machine learning algorithms were implemented and evaluated:

* Logistic Regression
* Random Forest
* XGBoost

Both centralized and federated versions of these models were tested to compare performance and effectiveness.

---

## 🔹 Explainable AI

Explainable AI (XAI) techniques were integrated to improve model transparency and interpretability.

### SHAP (Shapley Additive Explanations)

Used to identify global feature importance and understand the contribution of each feature to fraud predictions.

### LIME (Local Interpretable Model-Agnostic Explanations)

Used to explain individual transaction predictions and provide local interpretability for suspicious transactions.

---

## 🤖 Models Used

### Centralized Models

* Logistic Regression
* Random Forest
* XGBoost

### Federated Models

* Federated Logistic Regression
* Federated Random Forest
* Federated XGBoost

---

## 📈 Results

### Best Performance

* Accuracy: 88%
* Federated XGBoost achieved the strongest overall performance.

### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

The project successfully demonstrated the feasibility of privacy-preserving fraud detection using Federated Learning and Explainable AI techniques.

---

## 📊 Key Findings

* Transaction Hour strongly influences fraud detection.
* Transaction Amount plays a significant role in identifying suspicious activity.
* Fee-to-Amount Ratio is an important fraud indicator.
* Sender and Receiver transaction behaviour contribute significantly to model predictions.
* Federated Learning enables privacy-preserving model training without exposing raw transaction data.
* SHAP and LIME improve transparency and trust in fraud predictions.

---

## 💼 Business Impact

The proposed framework provides several business benefits:

* Detects suspicious cryptocurrency transactions in real time.
* Supports financial crime prevention strategies.
* Enhances customer trust through transparent AI decisions.
* Preserves user privacy through decentralized learning.
* Improves compliance with privacy regulations.
* Supports scalable fraud monitoring across multiple payment platforms.

---

## 🧠 Tech Stack

Python

Pandas

NumPy

Scikit-Learn

XGBoost

Federated Learning

SHAP

LIME

Matplotlib

Seaborn

Jupyter Notebook

---

## 📁 Project Structure

AI-Cryptocurrency-Fraud-Detection.ipynb

Cryptocurrency_Transaction_Dataset.csv

requirements.txt

README.md

images/

├── SHAP Analysis

├── LIME Explanations

├── Model Performance Results

└── Architecture Diagrams

---

## 🚀 Future Improvements

* Deploy the model using FastAPI or Flask.
* Develop a real-time fraud detection pipeline.
* Integrate blockchain-based transaction monitoring.
* Implement advanced Federated Learning frameworks.
* Improve fraud class recall and detection sensitivity.
* Explore deep learning techniques for fraud detection.
* Develop a production-ready dashboard for monitoring suspicious transactions.

---

## 📌 Conclusion

This project presents a comprehensive end-to-end framework for cryptocurrency fraud detection, utilizing Federated Learning and Explainable AI.

By combining privacy-preserving machine learning, advanced fraud detection algorithms, and interpretable AI techniques, the system provides a scalable and transparent solution for detecting suspicious cryptocurrency transactions in decentralized payment environments.

The project highlights the practical application of Artificial Intelligence, Machine Learning, Federated Learning, and Explainable AI in addressing modern cybersecurity and financial fraud challenges.
