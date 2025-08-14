# 🏗 Energy Efficiency Multi-Output Regression Model

## 📌 Overview
This project builds and optimizes a **multi-output regression model** to predict two target variables (`Y1` and `Y2`) from the **ENB2012 energy efficiency dataset**.  
It uses **Bayesian Optimization (Hyperopt)** to tune hyperparameters for **Random Forest** and **Gradient Boosting** regressors.

## 🚀 Features
- Data preprocessing: Missing value handling, duplicate removal, scaling, and outlier detection.
- Data visualization: Histograms, boxplots, and correlation heatmaps.
- Multi-output regression with **RandomForestRegressor** & **GradientBoostingRegressor**.
- **Bayesian optimization** for hyperparameter tuning.
- Model performance evaluation using RMSE and R² score.
- Trained model saved as `model.pkl`.

## 📊 Dataset
- **File:** ENB2012_data.csv
- **Shape:** 768 rows × 10 columns
- **Targets:** `Y1`, `Y2` (energy efficiency metrics)
- **Type:** Mixed numerical and categorical features.

## 📈 Model Performance
- **Best Params:** Found via Hyperopt
- **RMSE:** ~ (value from script output)
- **R² Score:** ~ (value from script output)

## ⚙️ Installation & Usage
```bash
# Install dependencies
pip install -r requirements.txt

# Run the script
python model.py
