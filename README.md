# wine-quality-ml-prediction
Final machine learning project using Python to predict wine quality and wine type (red or white) based on physicochemical properties. Built using classification and regression models, PCA, and visualization.

# Wine Quality Prediction

**Collaborators:** Leeza Sergeeva, Thomas Boisvert  
**Course:** MSDS 599 - Modeling II: Machine Learning  
**Institution:** University of San Francisco  

## 📌 Project Overview

This project explores supervised machine learning models to classify wines as red or white and predict their quality score (0–10) based on physicochemical properties.

We applied several models, including:
- Logistic Regression
- K-Nearest Neighbors
- Random Forest Classifier and Regressor
- Gradient Boosting
- Principal Component Analysis

## 📊 Dataset

Source: [UCI Machine Learning Repository](https://www.kaggle.com/datasets/rajyellow46/wine-quality)  
- Combined red and white wine datasets
- Features include acidity, sugar, pH, sulfur dioxide, alcohol, and more

## 🔧 Tools Used

- Python, Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn

## 📁 File Guide

- `notebooks/msds599_final_all.ipynb`: Main notebook with all analysis and modeling
- `data/winequalityN.csv`: Cleaned dataset used for training and evaluation
- `requirements.txt`: Python package dependencies

## ✅ Results

Our best-performing model for wine type classification:
- **Random Forest Classifier**  
  - R²: 0.993  
  - Precision: 0.996  
  - Recall: 0.975  
  - Accuracy: 0.993

For wine quality prediction, **Random Forest** again showed highest accuracy.

## 📌 Future Work

- Deploy as a web app for wine quality estimation
- Add interpretability (e.g. SHAP) for model explainability

