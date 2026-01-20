# Wrapper Feature Selection

A simple implementation of Wrapper Feature Selection technique in Python (Jupyter Notebook included).
Wrapper methods are a type of feature selection that evaluates subsets of features by training a model and selecting the best subset based on model performance.

## 📌 What This Project Does

- This project demonstrates how to use wrapper-based feature selection to:
- Select the most relevant features from a dataset
- Improve model performance
- Reduce dimensionality and training time

## 🧠 What Are Wrapper Methods?

Wrapper methods wrap feature selection around a machine learning model and iteratively search for the best subset of features using model evaluation. They are model-specific and can perform better than simple filter methods, though they are more computationally expensive.
*Common strategies include:*
- Forward selection – start with no features and add the best ones
- Backward elimination – start with all features and remove the least relevant
- Recursive feature elimination (RFE) – recursively remove least important features

## 📂 Included

wrapper-feature-selection.ipynb — Jupyter Notebook containing the code and explanation for wrapper feature selection.

## 🚀 How to Use

*Clone the repository:*

git clone https://github.com/vedantbhavsar17/wrapper-feature-selection.git

*Open the notebook in Jupyter:*

jupyter notebook wrapper-feature-selection.ipynb

Follow the notebook to see how feature subsets are chosen and evaluated.
