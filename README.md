🧠 Breast Cancer Prediction using Machine Learning
📌 Project Overview

This project builds a machine learning model to predict whether a breast tumor is benign or malignant based on diagnostic features.
The goal is to demonstrate an end-to-end ML workflow including data preprocessing, model training, evaluation, and prediction.

This project is designed to showcase Python, machine learning fundamentals, and analytical thinking for technical interviews.

📊 Dataset

Source: Breast Cancer Wisconsin Dataset (sklearn.datasets)

Samples: 569

Features: 30 numerical features derived from digitized images of breast mass

Target:

0 → Malignant

1 → Benign

⚙️ Machine Learning Pipeline

Load dataset

Exploratory Data Analysis (EDA)

Data preprocessing & scaling

Train–test split

Model training

Model evaluation

Prediction

🧪 Models Used

Logistic Regression

(Extendable to Random Forest, SVM, KNN)

📈 Evaluation Metrics

Accuracy

Confusion Matrix

Precision, Recall, F1-Score

🛠️ Tech Stack

Python

NumPy

Pandas

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

▶️ How to Run
pip install numpy pandas scikit-learn matplotlib seaborn
jupyter notebook


Open:
python breast_cancer_model.py

Breast_Cancer_ML.ipynb

🚀 Future Improvements

Hyperparameter tuning

Model comparison

Feature importance analysis

Convert model to REST API using FastAPI

Add CI/CD pipeline
