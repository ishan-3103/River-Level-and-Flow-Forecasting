# 🌊 River Level and Flow Forecasting using Deep Learning

A deep learning-based hydrological forecasting project developed during a research internship at the **CS & IT Department, Veermata Jijabai Technological Institute (VJTI), Mumbai**. This project investigates and compares multiple recurrent and hybrid neural network architectures for predicting river **water level** and **flow** using multivariate hydrological and meteorological time-series data.

---

## 📌 Project Overview

Accurate prediction of river water level and discharge is essential for flood forecasting, reservoir management, and water resource planning. This project explores several deep learning architectures and evaluates their effectiveness on multivariate hydrological time-series data collected from the Narmada River basin.

The study includes baseline recurrent neural networks, hybrid CNN-RNN models, Transformer-based architectures, and an xLSTM-inspired recurrent network.

---

## 🎯 Objectives

- Forecast river water level and flow using historical hydrological observations.
- Compare the performance of multiple deep learning architectures.
- Analyze the impact of hybrid feature extraction techniques on forecasting accuracy.
- Identify the most suitable architecture for multivariate hydrological time-series prediction.

---

## 🧠 Models Implemented

- Baseline LSTM
- Baseline GRU
- Separate LSTM Models
- Separate GRU Models
- CNN-LSTM
- CNN-GRU
- Transformer-CNN-LSTM
- xLSTM-Inspired Architecture

---

## ⚙️ Workflow

Raw Data
↓
Exploratory Data Analysis
↓
Data Cleaning & Missing Value Analysis
↓
Feature Engineering
↓
Sliding Window Sequence Generation
↓
Model Training
↓
Performance Evaluation
↓
Comparative Analysis

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

---

## 📁 Repository Structure

```
River-Level-and-Flow-Forecasting
│
├── Notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Preprocessing.ipynb
│   ├── ...
│
├── Outputs/
│   └── cnn_gru_flow.txt
│
└── README.md
```

---

## 🛠️ Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📂 Dataset

The dataset used in this project was provided for academic research purposes and is **not included** in this repository.

---

## 📈 Current Status

- ✔ Exploratory Data Analysis
- ✔ Data Preprocessing
- ✔ Baseline Models
- ✔ Hybrid Models
- ✔ Comparative Analysis
- ✔ Research Manuscript Preparation

---

## 🚀 Future Work

- Physics-Informed Neural Networks (PINNs)
- Integration of upstream meteorological data
- Hyperparameter optimization
- Explainable AI (SHAP/LIME)
- Real-time forecasting pipeline

---

## 👨‍💻 Author

**Ishan Pathak**

B.Tech Robotics & Artificial Intelligence  
COEP Technological University

GitHub: https://github.com/ishan-3103