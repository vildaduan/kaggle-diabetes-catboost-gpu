# Diabetes Prediction with CatBoost Classifier

This project addresses the Kaggle Tabular Playground Series 2025 challenge to predict the probability of diabetes diagnosis using tabular clinical data.

## Key Features
- GPU-accelerated CatBoostClassifier
- Handles categorical features natively
- Optimized for ROC-AUC metric
- Designed to run on Runpod GPU or local environments

## Model
- Algorithm: CatBoost (GPU)
- Evaluation metric: ROC-AUC
- Validation AUC: ~0.72

## Files
- `diabetes_catboost_gpu.ipynb`: Model training and submission notebook
- `requirements.txt`: Python dependencies

## How to Run
```bash
pip install -r requirements.txt
jupyter lab
