# Cyber-Attack Classification in Network Traffic

## 📌 Project Overview

This project focuses on developing a **multi-class machine learning-based classification model** to detect and classify various types of network intrusions and benign traffic patterns. It is built on two benchmark datasets:
- **NSL-KDD** — a refined version of the KDD’99 dataset
- **TON_IoT Combined Telemetry Dataset** — a realistic IoT-based intrusion dataset

The goal is to explore and compare the performance of multiple machine learning models on both datasets and present results through comparative analysis and rich visualizations.

## 🎯 Objectives

- Build predictive models using 6 different machine learning algorithms
- Evaluate and compare performance metrics: Accuracy, Precision, Recall, F1-Score, Error Rate, and False Positive Rate (FPR)
- Visualize results using heatmaps and bar graphs for better interpretability

---

## 📁 Datasets Used

### 1. NSL-KDD Dataset
- Cleaned and balanced version of KDD’99
- Contains 5 traffic classes: Benign, DOS, Probe, R2L, U2R

### 2. TON_IoT Combined Telemetry Dataset
- Contains telemetry data from IoT sensors and attack patterns
- Realistically simulates threats in IoT environments

---

## 🧠 Models Used

The following models were applied to both datasets:
- Decision Tree (DT)
- Random Forest (RF)
- Gaussian Naive Bayes (GNB)
- AdaBoost
- Multi-Layer Perceptron (MLP)
- K-Nearest Neighbors (KNN)

---

## 🔧 Tools & Libraries

- Python (Jupyter Notebooks)
- `pandas`, `numpy` — data manipulation
- `matplotlib`, `seaborn` — visualization
- `scikit-learn` — model training and evaluation

---

## 📊 Performance Summary

### ✅ Dataset 1: NSL-KDD

| Algorithm       | Accuracy | Precision | Recall | F1-Score | Error Rate |
|----------------|----------|-----------|--------|----------|------------|
| Decision Tree  | 0.76     | 0.81      | 0.76   | 0.73     | 0.23       |
| Random Forest  | 0.64     | 0.58      | 0.64   | 0.55     | 0.35       |
| Gaussian NB    | 0.49     | 0.65      | 0.49   | 0.50     | 0.50       |
| AdaBoost       | 0.52     | 0.83      | 0.51   | 0.62     | 0.33       |
| MLP            | 0.73     | 0.81      | 0.76   | 0.69     | 0.26       |
| KNN            | 0.75     | 0.81      | 0.76   | 0.71     | 0.24       |

> 💡 Best performers: **Decision Tree**, **KNN**, and **MLP**

---

### ✅ Dataset 2: TON_IoT

| Algorithm       | Accuracy | Precision | Recall | F1-Score | Error Rate |
|----------------|----------|-----------|--------|----------|------------|
| Decision Tree  | 1.00     | 1.00      | 0.76   | 1.00     | 0.00       |
| Random Forest  | 0.99     | 0.99      | 0.99   | 0.99     | 0.01       |
| Gaussian NB    | 0.99     | 0.66      | 0.49   | 0.78     | 0.34       |
| AdaBoost       | 1.00     | 1.00      | 1.00   | 1.00     | 0.00       |
| MLP            | 1.00     | 1.00      | 1.00   | 1.00     | 0.00       |
| KNN            | 1.00     | 1.00      | 1.00   | 1.00     | 0.00       |

> 💡 All algorithms achieved **very high accuracy**, with MLP, KNN, and AdaBoost achieving **perfect classification**.

---

## 📈 Visualizations

Each classifier’s performance was visualized using:
- **Heatmaps** for confusion matrices
- **Bar charts** comparing accuracy across classifiers

Visualizations make it easy for stakeholders to understand model performance across attack types.

---

## 💡 Key Insights

- The **TON_IoT dataset** yielded significantly better performance for all classifiers, indicating clearer class separability.
- **Decision Tree, MLP, and KNN** consistently performed well across both datasets.
- NSL-KDD remains a challenging dataset due to the complexity and imbalance in some attack categories.

---

## 👨‍💻 Author

**Mitul Tandon**  
Student ID: s223588983  
Security Analyst & Data Science Enthusiast  
[GitHub Repository](https://github.com/Mitul22/719_5.1HD_Task)

---

## 📚 References

A full list of references is included in the PDF report. These include academic papers, documentation from scikit-learn, analytics blogs, and dataset documentation.

---

## ✅ Conclusion

This project highlights the importance of applying multiple models, visualizing results, and interpreting performance across diverse datasets. The insights derived not only support cybersecurity use cases but also demonstrate practical machine learning applications in real-world network environments.
