# Wine Quality Prediction Analysis

This repository contains a machine learning project focused on predicting the quality of white wine based on its chemical properties. By utilizing the "Wine Quality" dataset, several regression and classification models were implemented to analyze the factors that contribute to high-quality wine.

## 📌 Project Overview
The goal of this project is to model wine quality based on physicochemical tests. This is a classic data science problem where we explore how variables like acidity, sugar levels, and alcohol content influence the final quality score assigned by experts.


## 📂 Repository Structure
The repository contains the following files:

* **`winequality_white.csv`**: The dataset containing chemical profiles of white wine samples.
* **`Decision_tree.ipynb`**: Implementation of the Decision Tree algorithm.
* **`Logistic_regression.ipynb`**: Predictive analysis using Logistic Regression.
* **`Random_forest_regression.ipynb`**: Implementation of the Random Forest Regressor.
* **`Support_vector_machine.ipynb`**: Implementation using Support Vector Machines (SVM).
* **`.gitignore`**: Configuration to exclude temporary files and checkpoints from the repo.
* **`LICENSE`**: MIT license for open-source use.

## 📊 Dataset Features
The dataset includes the following chemical attributes:
* **Fixed Acidity / Volatile Acidity / Citric Acid**
* **Residual Sugar**
* **Chlorides**
* **Free Sulfur Dioxide / Total Sulfur Dioxide**
* **Density**
* **pH**
* **Sulphates**
* **Alcohol**
* **Quality (Target):** Score between 0 and 10.

## 🚀 Getting Started

### Prerequisites
You will need Python 3.x and the following libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
