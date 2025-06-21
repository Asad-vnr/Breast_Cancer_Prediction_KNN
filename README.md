# Breast_Cancer_Prediction_KNN

🧠 Breast Cancer Prediction using K-Nearest Neighbors (KNN)

This project aims to predict whether a tumor is malignant or benign using the K-Nearest Neighbors (KNN) classification algorithm. The model is trained on the Breast Cancer Wisconsin Diagnostic Dataset, a widely used dataset in medical research and machine learning applications.
📌 Table of Contents

    Overview

    Dataset

    Tech Stack

    Steps Performed

    Results

    How to Run

    Screenshots

    License

📖 Overview

The goal of this project is to build a machine learning model that can classify tumors as either benign or malignant based on various features derived from breast mass images. The KNN algorithm is chosen for its simplicity and efficiency in classification tasks, especially in the medical domain.
📊 Dataset

    Source: https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset

    Target: diagnosis (M = malignant, B = benign)

    Rows: 569

    Columns: 32

🛠 Tech Stack

    Python 🐍

    Jupyter Notebook 📒

    Libraries:

        pandas, numpy — Data handling

        matplotlib, seaborn — Data visualization

        scikit-learn — ML model building and evaluation

🔍 Steps Performed

    Importing Libraries

    Loading Dataset

    Exploratory Data Analysis (EDA)

    Data Cleaning

        Handling missing values

        Dropping irrelevant columns

    Label Encoding

    Feature Scaling

    Train-Test Split

    Model Building using KNN

    Hyperparameter Tuning (choosing best K)

    Evaluation

        Accuracy Score

        Confusion Matrix

        Classification Report

✅ Results

    Best K Value: Determined using elbow method or manual iteration

    Model Accuracy: ~97%

    Inference: The model efficiently classifies breast cancer tumors with high accuracy and can be extended into real-time diagnostic support tools.
