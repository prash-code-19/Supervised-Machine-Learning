# Machine Learning Algorithms

This folder contains Jupyter notebooks exploring supervised machine learning algorithms, along with datasets used by some of the examples.

## Contents

| Folder | Topics and notebooks |
|---|---|
| `Decision_Tree/` | Decision tree classification (`classification_tree.ipynb`) and regression (`regressor_tree.ipynb`) |
| `KNN/` | K-nearest neighbors (`kNN.ipynb`) and `heart.csv` |
| `Linear_Regression/` | Linear regression (`LR_1.ipynb`), regularization (`regularization.ipynb`), and `insurance.csv` |
| `Logistic_Regression/` | Logistic regression (`logist.ipynb`) and `heart.csv` |
| `Naive_Bayes/` | Naive Bayes (`naive_bayes.ipynb`) and `heart.csv` |
| `SVM/` | Support vector machine classification (`svm_classifier.ipynb`) and regression (`svm_regressor.ipynb`) |
| `scratch_implementation/` | Notebook implementations of KNN classification, linear regression, and logistic regression |

## Getting Started

1. Install Python 3 and Jupyter Notebook or JupyterLab.
2. Clone or download this repository.
3. Open a terminal in this folder and start Jupyter:

   ```bash
   jupyter lab
   ```

   Or use `jupyter notebook` if you prefer the classic interface.
4. Open a notebook from the relevant folder and run its cells.

Install any Python packages imported by a notebook in your active environment before running it. Dataset paths in the notebooks may assume they are run from their containing folder.

## Datasets

CSV files used by the examples are stored alongside their notebooks. Check the relevant notebook for details about its data and any expected preprocessing.
