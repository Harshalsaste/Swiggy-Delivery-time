
***

# Swiggy Delivery Time Prediction

This repository contains a comprehensive **Data Science and Machine Learning workflow** designed to predict the estimated delivery time for Swiggy food orders. The project focuses on the analytical and modeling stages of the machine learning lifecycle, including data preprocessing, experimentation with missing data strategies, and advanced ensemble modeling.

## 📋 Project Overview
The primary goal of this project is to build a robust regression model that can accurately estimate delivery times based on various order and delivery characteristics. The workflow emphasizes rigorous experimentation and hyperparameter optimization to ensure the highest possible model accuracy.

## 📂 Repository Structure (Notebooks)
The project is organized into several Jupyter notebooks located in the `notebooks/` directory, reflecting each stage of the development process:

### 1. Data Preparation & Exploration
*   **`Food_Delivery_Data_Cleaning.ipynb`**: Initial data cleaning, handling formatting issues, and preparing the raw dataset for analysis.
*   **`Food_Delivery_EDA.ipynb`**: Exploratory Data Analysis to identify trends, outliers, and key features that influence delivery times.

### 2. Feature Engineering & Experiments
*   **`Food Delivery Exp 1 drop vs impute.ipynb`**: An experiment comparing the performance of dropping missing values versus using imputation techniques.
*   **`Food Delivery Exp 2 missing indicator.ipynb`**: Testing the effectiveness of adding missing value indicators to improve model performance.

### 3. Model Selection & Tuning
*   **`Food Delivery Model Selection.ipynb`**: Evaluation of various machine learning algorithms to select the best-performing baseline models.
*   **Hyperparameter Tuning**: Dedicated notebooks for optimizing specific algorithms:
    *   `Food Delivery RF HP Tuning.ipynb` (Random Forest).
    *   `Food Delivery LGBM HP Tuning.ipynb` (LightGBM).
    *   `Food Delivery Stacking Regressor HP Tuning.ipynb` (Ensemble Stacking).

### 4. Final Implementation
*   **`Food Delivery Final Estimator.ipynb`**: The implementation of the final, optimized model incorporating the best parameters and strategies identified in previous steps.

## 🚀 Key Features
*   **End-to-End Analysis**: Covers everything from raw data cleaning to a final tuned estimator.
*   **Rigorous Experimentation**: Includes comparative studies on handling missing data to ensure data integrity.
*   **Advanced Modeling**: Utilizes sophisticated techniques like **Stacking Regressors** and **LightGBM** to capture complex patterns in delivery data.
*   **Optimized Performance**: Extensive hyperparameter tuning for multiple model types.

## 🛠️ Tech Stack
*   **Language**: Python
*   **Libraries**: Pandas, NumPy, Scikit-learn, LightGBM, Matplotlib, Seaborn


***

