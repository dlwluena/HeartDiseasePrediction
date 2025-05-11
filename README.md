# 🫀 Heart Disease Prediction Project

This project uses a PyTorch-based deep learning model to predict the presence of heart disease from patient data.

# Aim of this Project

This project focuses on developing a deep learning model to predict the presence of heart disease based on patient health data. It uses various medical features such as age, cholesterol level, blood pressure, and more, to train a binary classifier. The final goal is to support early diagnosis and enhance healthcare decision-making through AI.

# Technologies and Libraries Used
- torch
- Python 3
- PyTorch
- Pandas & NumPy
- scikit-learn
- Matplotlib (optional for visualization)


# Data Preparation
- Dataset: [`heart.csv`](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction) from Kaggle
- Source: Combined dataset from Cleveland, Hungarian, Switzerland, Long Beach VA, and Statlog (Heart) datasets
- Split: 70% training, 15% validation, 15% testing
- Preprocessing:
  - Features are normalized for better


# Model Architecture
- 3-layer fully connected neural network
- ReLU activations in hidden layers, Sigmoid in output
- Loss function: Binary Cross Entropy
- Optimizer: Adam

# Training & Evaluation
- Batched training with DataLoader
- Evaluated using accuracy and confusion matrix
- Overfitting/underfitting checked

## 📁 Project Structure

| File/Folder         | Description                                |
|---------------------|--------------------------------------------|
| `disease.ipynb`     | Main Jupyter Notebook with all steps       |
| `heart.csv`         | Dataset containing patient medical records |
| `README.md`         | Project overview and documentation         |

