# Task-08-House-Price-Prediction

# Task 08: Improving House Price Predictions through Feature Engineering

## 🔍 Objective
Use feature engineering and machine learning techniques to predict house prices using the Boston Housing dataset.

## 📁 Dataset
- Dataset used: `boston.csv`
- Source: Preloaded CSV version of the Boston Housing dataset.

## 🔧 Tools Used
- Python
- Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn

## 🧠 Techniques Applied
- Checked and handled skewness using `np.log1p`
- Log-transformed target variable `MEDV`
- Trained `RandomForestRegressor` model
- Visualized feature importance
- Calculated RMSE for model evaluation

## 📊 Output
- Top features: `LSTAT`, `RM`, `CRIM`, etc.
- RMSE: ~0.1491
- Feature importance chart included (see screenshot)

## 📎 Files Included
- `task08_boston.ipynb` - Jupyter notebook with code
- `boston.csv` - Dataset

## ✅ Result
Successfully applied feature engineering techniques to improve model accuracy.
