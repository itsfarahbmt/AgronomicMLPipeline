
# 🌱 Agronomic Machine Learning Pipeline

This project implements a complete machine learning pipeline on **agronomic data**, focusing on predicting agricultural parameters such as water consumption and crop yield.  
It combines **data preprocessing**, **model training**, and **hyperparameter optimization** using **Scikit-learn** and **Pandas**.

---

## 📌 Objectives
- Build a robust **data ingestion pipeline** for agronomic datasets (CSV, Excel).
- Perform **data cleaning, renaming, and fusion** for consistent preprocessing.
- Train baseline models:
  - **Random Forest Regressor**
  - **Multi-Layer Perceptron (MLP) Regressor**
- Optimize hyperparameters using **GridSearchCV**.
- Evaluate and compare models using performance metrics.
---


## ⚙️ Pipeline Overview
1. **LoadData.py** → Load raw datasets and verify integrity.  
2. **Renommage.py** → Standardize and clean column names.  
3. **CleanFusion.py** → Handle missing values, duplicates, and merge datasets.  
4. **Data_pipeline.py** → Apply preprocessing (scaling, encoding, normalization).  
5. **Train_model.py** → Train baseline Random Forest and MLP regressors.  
6. **OptimParFor.py** → Optimize Random Forest with GridSearchCV.  
7. **OptimParMLP.py** → Optimize MLP with GridSearchCV.  
8. **EvaluateModels.py** → Compare model performance (MSE, RMSE, MAE, R²).  

---

## 📊 Models & Metrics
- **Random Forest Regressor**: interpretable model with feature importance analysis.  
- **MLP Regressor**: neural network for capturing nonlinear relationships.  

Evaluation metrics include:
- **MSE** (Mean Squared Error)  
- **RMSE** (Root Mean Squared Error)  
- **MAE** (Mean Absolute Error)  
- **R² Score**  

---

##📜 License
This project is for academic purposes.
