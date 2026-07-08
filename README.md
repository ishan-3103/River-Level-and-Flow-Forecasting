# 🌊 River Level and Flow Forecasting using Deep Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red?logo=keras)
![Status](https://img.shields.io/badge/Status-Research%20Project-success)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter)

---

## 📖 Overview

This repository contains the implementation of multiple **Deep Learning** and **Hybrid Neural Network** architectures for **river water level** and **river flow forecasting** using multivariate hydrological and meteorological time-series data.

The work was carried out during a **Research Internship** at the **CS & IT Department, Veermata Jijabai Technological Institute (VJTI), Mumbai**.

The objective of this research is to investigate different recurrent and hybrid deep learning architectures and compare their performance for hydrological forecasting.

---

## 🎯 Objectives

- Forecast river water level and river flow using historical observations.
- Compare standalone recurrent neural networks with hybrid architectures.
- Study the impact of CNN-based feature extraction on forecasting.
- Analyze different deep learning architectures for multivariate time-series prediction.
- Evaluate model performance using multiple statistical metrics.

---

## 🧠 Deep Learning Models Implemented

| Category | Models |
|-----------|--------|
| Baseline Models | LSTM, GRU |
| Separate Models | LSTM (Level), LSTM (Flow), GRU (Level), GRU (Flow) |
| Hybrid Models | CNN-LSTM, CNN-GRU |
| Transformer Models | Transformer-CNN-LSTM |
| Advanced Recurrent Models | xLSTM-Inspired Architecture |

---

## 🔄 Project Workflow

```text
Raw Hydrological Data
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Missing Value Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Sliding Window Sequence Generation
        │
        ▼
Model Training
        │
        ▼
Performance Evaluation
        │
        ▼
Comparative Analysis
```

---

## 📊 Dataset Information

| Attribute | Details |
|------------|---------|
| River Basin | Narmada |
| Time Period | 2000–2021 |
| Number of Stations | 5 |
| Forecast Targets | River Water Level & Flow |
| Input Features | Hydrological & Meteorological Parameters |

> **Note:** The dataset is **not included** in this repository as it was used for academic research purposes.

---

## 🏆 Best Performing Models

| Task | Best Model | Best Performance |
|------|------------|-----------------|
| Best Level Prediction | CNN-GRU | RMSE = **10.91** |
| Best Flow Prediction | CNN-GRU | R² = **0.126** |
| Lowest Level MAE | Separate LSTM | **10.84** |
| Lowest Flow MAE | Transformer-CNN-LSTM | **49.82** |

---

## 📈 Experimental Summary

- ✔ Implemented **12 deep learning experiments**
- ✔ Compared **6 different neural network architectures**
- ✔ Developed baseline, hybrid, transformer, and xLSTM-inspired models
- ✔ Performed extensive preprocessing and feature engineering
- ✔ Evaluated models using RMSE, MAE, and R² Score

---

## 🛠️ Technologies Used

### Programming Languages

- Python

### Machine Learning & Deep Learning

- TensorFlow
- Keras
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

### Development Tools

- Jupyter Notebook
- Git
- GitHub
- VS Code

---

## 📂 Repository Structure

```text
River-Level-and-Flow-Forecasting/
│
├── Notebooks/
│   ├── 01_EDA.ipynb
│   ├── 02_Preprocessing.ipynb
│   ├── 03_LSTM.ipynb
│   ├── 04_GRU.ipynb
│   ├── ...
│
├── Outputs/
│   └── cnn_gru_flow.txt
│
├── README.md
└── .gitignore
```

---

## 📊 Evaluation Metrics

The models were evaluated using:

- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- R² Score

---

## 🔬 Future Improvements

- Physics-Informed Neural Networks (PINNs)
- Attention-based sequence models
- Explainable AI (SHAP/LIME)
- Hyperparameter optimization
- Multi-step forecasting
- Real-time deployment pipeline

---

## 👨‍💻 Author

**Ishan Pathak**

B.Tech Robotics & Artificial Intelligence

COEP Technological University

Phone no.: 7066411683

📧 ishanpathak3103@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/ishan-pathak-435194326/

🔗 GitHub: https://github.com/ishan-3103

---

## ⭐ If you found this repository useful, consider giving it a star!