# Boston Mortgage Application Analysis

## Description

A CSCI 381 notebook analyzing mortgage application denials using the bundled `HDMA Boston Housing Data.csv`. It explores applicant attributes and compares three logistic regression models.

## Dependencies

Python 3, Jupyter Notebook or Google Colab, pandas, NumPy, Matplotlib, Seaborn, and scikit-learn. Package versions are not pinned.

## Technologies

Python notebooks, pandas data preparation, Seaborn and Matplotlib plots, and scikit-learn classification.

## Setup

```bash
git clone https://github.com/bryan3342/Boston-Housing-data.git
cd Boston-Housing-data
python -m venv .venv
source .venv/bin/activate
python -m pip install notebook pandas numpy matplotlib seaborn scikit-learn
```

On Windows, activate the environment with `.venv\Scripts\activate` instead.

The notebook loads the CSV from this repository through a raw GitHub URL, so its default loading cell requires internet access. For local use, change that URL to `HDMA Boston Housing Data.csv`.

## Features

- CSV parsing, numeric conversion, and categorical encoding.
- Distribution plots and correlation heatmaps.
- Stratified training and test split.
- Three logistic regression feature sets with accuracy, precision, recall, F1, and ROC-AUC comparisons.

This is an analysis notebook, not a deployed lending decision service.

## Commands to run

```bash
jupyter notebook B_Mejia_Quiz4.ipynb
```

Run the cells in order. There is no separate application or test command.

## Contributors

- [Bryan Mejia (@bryan3342)](https://github.com/bryan3342), credited in Git history.
