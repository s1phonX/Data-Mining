# CS 6220 Homework 1 - Iris Classification Pipeline

This project tests a Python data-mining environment by training and evaluating a scikit-learn pipeline on the Iris flower dataset.

## Setup

1. Open this `HW_1` folder in Visual Studio Code.
2. Create and activate a Python virtual environment if desired.
3. Install dependencies:

   ```powershell
   python -m pip install -r requirements.txt
   ```

4. Open `homework_1.ipynb` in VS Code and select a Python kernel.
5. Run all cells from top to bottom before committing the notebook.

## Contents

The notebook loads the Iris data, inspects and visualizes it, creates an 80/20 stratified train-test split, trains a scaled logistic-regression pipeline, measures training and testing time, reports accuracy, plots a confusion matrix, and explores the `C` hyperparameter.

## Reproducibility

The notebook uses `random_state=42` for a reproducible split and model configuration.
