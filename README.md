# anomaly
Anomaly Detection Models Performance Evaluation



This repository contains an analysis of multiple anomaly detection models applied to the PyCaret anomaly dataset. The project aims to evaluate and compare the performance of various models in identifying anomalies and clustering behavior before and after prediction.


Project Overview


The goal of this project is to:

Apply different anomaly detection models.


Compare their performance based on silhouette scores.


Analyze the number of anomalies detected before and after predictions.


Investigate the number of clusters formed by each model.


Models Evaluated:

ABOD (Angle-Based Outlier Detection)


Cluster-Based Local Outlier Factor (CBLOF)


COF (Connectivity-Based Outlier Factor)


IForest (Isolation Forest)


Histogram-Based Outlier Detection


KNN (K-Nearest Neighbors)


LOF (Local Outlier Factor)


SVM (Support Vector Machine for Outliers)


PCA (Principal Component Analysis)


MCD (Minimum Covariance Determinant)


SOD (Subspace Outlier Detection)


SOS (Stochastic Outlier Selection)


Dataset:
The anomaly dataset is a built-in dataset from PyCaret's anomaly detection module. It is used to train and evaluate the models for anomaly detection.

Performance Metrics:
The models are evaluated based on:


Silhouette Score: Measures how well samples are clustered.
Positive scores indicate good clustering.
Negative scores suggest poor clustering.


Number of Anomalies:
Before Prediction: Number of anomalies detected during model training.
After Prediction: Number of anomalies when the model is applied to new data.
Clusters Before and After Prediction:
Clusters detected before and after applying the model.

![Screenshot 2024-11-28 075421](https://github.com/user-attachments/assets/79196dd7-d858-4b22-a34f-9ef8d6a0db16)

Observations:


Models like MCD and Histogram-Based had the highest silhouette scores, indicating better clustering performance.
ABOD failed to detect any anomalies after prediction, showing only 1 cluster.
KNN and LOF models show a slight drop in anomalies after prediction.


Conclusion


This project provides insights into the strengths and limitations of different anomaly detection models. MCD and Histogram-Based models perform well in terms of clustering quality, as evidenced by their high silhouette scores.
