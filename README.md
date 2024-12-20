---

## **Anomaly Detection Models Performance Evaluation**

This repository contains an analysis of multiple **anomaly detection models** applied to the PyCaret anomaly dataset. The project aims to **evaluate and compare** the performance of various models in identifying anomalies and clustering behavior before and after prediction.

---

### **Project Overview**

The goal of this project is to:

- **Apply different anomaly detection models** to the dataset.
- **Compare the models’ performance** based on **silhouette scores**.
- **Analyze the number of anomalies** detected **before and after predictions**.
- **Investigate the number of clusters** formed by each model.

---

### **Models Evaluated**

The following **anomaly detection models** were applied:

- **ABOD** (Angle-Based Outlier Detection)  
- **CBLOF** (Cluster-Based Local Outlier Factor)  
- **COF** (Connectivity-Based Outlier Factor)  
- **IForest** (Isolation Forest)  
- **Histogram-Based Outlier Detection**  
- **KNN** (K-Nearest Neighbors)  
- **LOF** (Local Outlier Factor)  
- **SVM** (Support Vector Machine for Outliers)  
- **PCA** (Principal Component Analysis)  
- **MCD** (Minimum Covariance Determinant)  
- **SOD** (Subspace Outlier Detection)  
- **SOS** (Stochastic Outlier Selection)

---

### **Dataset**

The **anomaly dataset** is a built-in dataset from PyCaret's anomaly detection module. This dataset is used to train and evaluate the models for **anomaly detection**.

---

### **Performance Metrics**

The models are evaluated based on the following metrics:

- **Silhouette Score**: Measures how well samples are clustered. Positive scores indicate good clustering, while negative scores suggest poor clustering.  
- **Number of Anomalies**:  
   - **Before Prediction**: Number of anomalies detected during model training.  
   - **After Prediction**: Number of anomalies detected when the model is applied to new data.  
- **Clusters Before and After Prediction**: Analyzes the clusters detected before and after applying the model to the dataset.

---

This project provides a comprehensive evaluation of various anomaly detection models, allowing for an in-depth comparison of their performance and clustering behaviors. 🚀


![Screenshot 2024-11-28 075421](https://github.com/user-attachments/assets/79196dd7-d858-4b22-a34f-9ef8d6a0db16)
---

## **Observations**

- Models like **MCD** and **Histogram-Based** had the **highest silhouette scores**, indicating **better clustering performance**.
- **ABOD** failed to detect any anomalies after prediction, showing only **1 cluster**.
- **KNN** and **LOF** models showed a slight **drop in anomalies after prediction**, indicating that their performance slightly degraded when applied to new data.

---

## **Conclusion**

This project provides insights into the **strengths and limitations** of different anomaly detection models.  
- **MCD** and **Histogram-Based models** perform well in terms of **clustering quality**, as evidenced by their **high silhouette scores**.
- Further analysis is required to understand the reasons behind the poor performance of models like **ABOD** and the slight performance drop seen in **KNN** and **LOF**.

---

This evaluation highlights key factors that influence the effectiveness of anomaly detection models and provides a foundation for selecting the right model for different anomaly detection tasks. 🚀
