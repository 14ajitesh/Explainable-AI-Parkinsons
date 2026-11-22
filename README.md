# Explainable AI for Parkinson's Disease Progression Prediction

## Overview

This project explores the prediction of Parkinson's disease progression using voice-based biomarkers and explainable deep learning techniques.

The project compares traditional machine learning and deep learning models, including Random Forest, LSTM, Transformer, and a proposed Feature-Aware Enhanced Temporal Transformer (FAETT).

The goal is to predict disease progression using the total Unified Parkinson's Disease Rating Scale (total_UPDRS) and improve model interpretability through attention mechanisms and SHAP analysis.

## Models

- Random Forest
- Long Short-Term Memory (LSTM)
- Transformer
- Feature-Aware Enhanced Temporal Transformer (FAETT)

## Explainable AI

The project uses:

- SHAP analysis for feature importance
- Attention visualization to understand temporal relationships
- Prediction and residual analysis for model evaluation

## Dataset

The project uses the UCI Parkinson's Telemonitoring Dataset, which contains voice measurements from individuals with Parkinson's disease.

## Technologies

Python, NumPy, Pandas, Scikit-learn, TensorFlow/Keras, Matplotlib, SHAP

## Project Structure

```text
Explainable-AI-Parkinsons/
├── uci_parkinson.ipynb
├── Untitled8.ipynb
├── README.md
└── model_comparison_results.csv
```

## Results

Model performance is evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

Final results will be reported after the models are rerun using a consistent preprocessing and evaluation pipeline.

## Future Work

- Improve reproducibility across model experiments
- Evaluate generalization to unseen subjects
- Refine SHAP and attention-based explanations
- Develop a user-friendly prediction interface

## Disclaimer

This project is for academic and research purposes only. It is not intended for clinical diagnosis or medical decision-making.
