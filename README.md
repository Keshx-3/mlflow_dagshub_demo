# MLflow Model Management with DAGsHub

This project explores **MLflow’s experiment tracking and model registry** with an **end-to-end workflow** on **DAGsHub**. It demonstrates how to manage ML experiments, track model performance, and implement a **Champion-Challenger framework**.

## 📌 Project Overview
- **Data Generation**: Created an **imbalanced dataset** using `make_classification`.
- **Model Training**: Trained **Logistic Regression, Random Forest, XGBoost**, and **SMOTETomek-balanced XGBoost** models.
- **Experiment Tracking**: Logged **metrics, parameters, and models** in MLflow.
- **DAGsHub Integration**: Set up a **remote MLflow tracking server** on DAGsHub.
- **Model Registry**: Implemented a **Champion-Challenger model framework** for comparing models.

## 🛠️ Technologies Used
- **Python**
- **MLflow** for experiment tracking
- **DAGsHub** for centralized MLflow tracking and collaboration
- **scikit-learn, XGBoost** for model training
- **SMOTETomek** for handling class imbalance

## 🚀 Why DAGsHub?
🔹 **Version Control for Code + Data** 📁  
🔹 **Centralized Experiment Tracking with MLflow** 📊  
🔹 **Collaboration for ML Teams** 👥  

## 📂 Repository Structure
```
├── data/                # Synthetic dataset
├── models/              # Saved models
├── notebooks/           # Jupyter notebooks for experimentation
├── src/                 # Source code for training and tracking
│   ├── train.py         # Model training script
│   ├── track_mlflow.py  # MLflow tracking script
├── README.md            # Project documentation
└── requirements.txt     # Required dependencies
```

## 🔗 Links
- **MLflow Experiment Tracking**: [DAGsHub Link]
- **Project Code**: [GitHub Link]

Would love to get feedback or contributions—feel free to check it out! 🚀
