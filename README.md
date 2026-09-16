# Diabetes Prediction Using Machine Learning

This repository contains the notebooks, datasets, preprocessing outputs, visualizations, and final report for a diabetes prediction machine-learning project.

## Project structure

```text
Diabetes-Prediction-ML/
├── data/
│   ├── raw/                 # Original dataset
│   ├── interim/             # Intermediate data files
│   └── processed/           # Cleaned / encoded / pipeline data
├── notebooks/
│   ├── preprocessing/       # Data cleaning and categorical encoding
│   └── models/              # Machine-learning model notebooks
├── results/
│   ├── figures/             # EDA / preprocessing visualizations
│   └── outputs/             # Reserved for generated prediction outputs
├── models/                  # Saved trained model files, if generated
├── reports/                 # Final project report
├── requirements.txt
├── .gitignore
└── README.md
```

## Models included

The model notebooks cover:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Random Forest
- Support Vector Machine (SVM)
- Artificial Neural Network (ANN)
- XGBoost

There are two KNN notebook versions in the supplied project files.

## Recommended workflow

1. Start with the notebooks in `notebooks/preprocessing/`.
2. Use the processed datasets in `data/processed/`.
3. Run the model notebooks in `notebooks/models/`.
4. The XGBoost notebook contains code for saving trained pipeline/model files to the `models/` / output location used by the notebook.
5. Read the final report in `reports/`.

## Running the notebooks

Create a Python environment and install the dependencies:

```bash
pip install -r requirements.txt
```

Then open the notebooks with Jupyter Notebook, JupyterLab, or Google Colab.

> Note: The supplied notebooks were originally prepared for notebook/Colab-style execution. Some file paths may need to be adjusted to match this repository structure before running locally.

## Data

The repository contains the supplied diabetes prediction dataset and processed versions used during the project. Check the dataset/source requirements applicable to your course or institution before publishing the data publicly.

## Report

The final report is included in `reports/Diabetes_Prediction_Using_Machine_Learning_Final_Report.pdf`.
