# Lipophilicity prediction using GNNs
# Molecular Lipophilicity Prediction

## Overview

This repository contains multiple Jupyter notebooks focused on predicting molecular lipophilicity using deep learning models implemented in PyTorch. The project is based on the SMILES (Simplified Molecular Input Line Entry System) representation of molecular structures and aims to provide accurate lipophilicity predictions.

The main notebooks in the project include:
- **predict_from_SMILES.ipynb**: Notebook for generating predictions based on molecular SMILES representations.
- **pytorch_lipo_classification.ipynb**: Notebook implementing a classification model for molecular lipophilicity prediction.
- **pytorchg_lipo.ipynb**: Initial notebook focused on developing a deep learning model for lipophilicity prediction.
- **pytorchg_lipo_crossval.ipynb**: This notebook incorporates cross-validation techniques to improve the lipophilicity model's generalizability.
- **pytorchg_lipo_final.ipynb**: The final model implementation for molecular lipophilicity prediction.
- **pytorchg_lipo_optuna.ipynb**: Notebook focusing on hyperparameter optimization using Optuna to enhance model performance.

## Requirements

To run this project, you need the following dependencies:
- Python 3.x
- PyTorch
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib
- RDKit (for SMILES parsing)
- Optuna (for hyperparameter optimization)

You can install the dependencies using the following command:

```bash
pip install -r requirements.txt
