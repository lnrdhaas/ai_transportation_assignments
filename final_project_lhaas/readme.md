# 🚦 Traffic Flow Prediction Project

This repository contains all code used during the traffic prediction project. The goal was to develop and evaluate models capable of accurately predicting short-term traffic flow.
## 📂 Project Structure

The codebase is organized to ensure a clear separation between training and evaluation.

| Folder/File | Description |
|--------------|-------------|
| **`preprocessing_train.py`** | Preprocessing pipeline for training data — cleaning, feature engineering, and saving processed datasets. |
| **`preprocessing_eval.py`** | Preprocessing for evaluation data using the same transformations as during training. |
| **`train_model.py`** | Model training and validation. Includes multiple algorithms (e.g., Linear Regression, XGBoost, Neural Networks). |
| **`evaluate_model.py`** | Evaluation of trained models on unseen data. Generates metrics and visualizations for comparison. |
