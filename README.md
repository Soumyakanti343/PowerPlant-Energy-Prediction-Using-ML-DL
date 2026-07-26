#  Power Plant Energy Output Prediction using Machine Learning & Deep Learning (PyTorch)

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![PyTorch](https://img.shields.io/badge/PyTorch-Deep%20Learning-red)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-F37626)
![License](https://img.shields.io/badge/License-MIT-green)

##  Project Overview

This project predicts the **Electrical Energy Output (PE)** of a Combined Cycle Power Plant using both **Machine Learning** and **Deep Learning (PyTorch)** techniques.

The project performs complete data preprocessing, feature scaling, model training, **5-Fold Cross Validation**, evaluation using multiple regression metrics, and compares the performance of different algorithms.

The objective is to determine the best-performing regression model for predicting power plant energy output.

---

##  Dataset

The dataset contains operational parameters collected from a Combined Cycle Power Plant.

### Features

| Feature | Description |
|----------|-------------|
| **AT** | Ambient Temperature |
| **V** | Exhaust Vacuum |
| **AP** | Ambient Pressure |
| **RH** | Relative Humidity |

### Target Variable

| Target | Description |
|---------|-------------|
| **PE** | Energy Output |

---

##  Project Workflow

```
Load Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Scaling
      │
      ▼
Train-Test Split
      │
      ▼
5-Fold Cross Validation
      │
      ▼
Machine Learning Models
      │
      ├── Linear Regression
      ├── KNN Regressor
      ├── Support Vector Regressor
      └── Random Forest Regressor
      │
      ▼
Deep Learning
      │
      └── Feed Forward Neural Network (PyTorch)
      │
      ▼
Evaluation Metrics
      │
      ▼
Visualization
      │
      ▼
Model Comparison
```

---

##  Machine Learning Models

- Linear Regression
- K-Nearest Neighbors (KNN)
- Support Vector Regressor (SVR)
- Random Forest Regressor

---

##  Deep Learning Model

A Feed Forward Neural Network (FNN) implemented using **PyTorch**.

### Architecture

```
Input Layer (4 Features)

        │

Hidden Layer (64 Neurons)
        ReLU

        │

Hidden Layer (32 Neurons)
        ReLU

        │

Hidden Layer (16 Neurons)
        ReLU

        │

Output Layer (1 Neuron)
```

---

##  Evaluation Metrics

The models are evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

##  Visualizations

The project includes:

- Correlation Heatmap
- Actual vs Predicted Plot
- Residual Plot
- Random Forest Feature Importance
- Training Loss Curve
- Validation Loss Curve
- MAE Comparison
- MSE Comparison
- RMSE Comparison
- R² Score Comparison
- Final Model Leaderboard

---

##  Model Performance

| Rank | Model |
|------|-------|
| 🥇 | Random Forest |
| 🥈 | KNN Regressor |
| 🥉 | Support Vector Regressor |
| 🏅 | Feed Forward Neural Network |
| 🏅 | Linear Regression |

---

##  Project Structure

```
PowerPlant-Energy-Prediction-Using-ML-DL/
│
├── Dataset/
│   └── power-plant.csv
│
├── Notebook/
│   └── PowerPlant_Energy_Prediction.ipynb
│
├── Images/
│   ├── Architecture.png
│   ├── correlation_heatmap.png
│   ├── feature_importance.png
│   ├── loss_curve.png
│   ├── leaderboard.png
│   └── model_comparison.png
│
├── README.md
└── Requirments.txt
```

---

##  Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-Learn
- PyTorch
- Jupyter Notebook

---

##  Key Features

- Complete Data Preprocessing
- Feature Scaling using StandardScaler
- 5-Fold Cross Validation
- Four Machine Learning Regression Models
- Deep Learning using PyTorch
- Performance Comparison
- Interactive Visualizations
- Model Leaderboard
- Feature Importance Analysis
- Professional Notebook Structure


---

##  Results

- Random Forest achieved the best prediction performance.
- Deep Learning (PyTorch FNN) produced competitive results.
- Cross Validation improved model reliability.
- Comparative analysis identified the most suitable regression model for this dataset.

---

##  Future Improvements

- Hyperparameter Optimization
- XGBoost Regressor
- LightGBM
- CatBoost
- Explainable AI (SHAP/LIME)
- Model Deployment using Streamlit or Flask
- Real-time Energy Prediction Dashboard

---

##  Author

**Soumya Kanti Upadhyay**

B.Tech in Computer Science & Engineering  
Jalpaiguri Government Engineering College

---
