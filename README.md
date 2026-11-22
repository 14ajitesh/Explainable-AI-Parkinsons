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

## Project Structure

- `uci_parkinson.ipynb` — Main notebook for model training and experiments.
- `Untitled8.ipynb` — Additional analysis and visualizations.
- `parkinsons_updrs.data` — Parkinson's telemonitoring dataset.
- `parkinsons_updrs.names` — Dataset description.
- `requirements.txt` — Python dependencies.
- `src/` — Directory for reusable source code.

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- TensorFlow
- Matplotlib and Seaborn
- SHAP
- Jupyter Notebook

## How to Run

1. Open the main notebook `uci_parkinson.ipynb`.
2. Upload the notebook to Google Colab or open it using Jupyter Notebook.
3. Install the required dependencies listed in `requirements.txt`.
4. Make sure the Parkinson's dataset files are available in the notebook's working directory.
5. Run the notebook cells in order to execute the experiments.

## Reproducibility

Model results may vary depending on preprocessing, train-test split, random seed, and training configuration. Refer to the notebook for the experiment implementation and reported results.
