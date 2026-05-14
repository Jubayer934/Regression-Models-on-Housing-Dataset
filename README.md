# 🏠 Regression Models on Housing Dataset
 
Comparing **Linear**, **Ridge**, and **Lasso** regression models on the Boston Housing Dataset to predict median house prices (`MEDV`).
 
---
 
## 📊 Dataset
 
506 samples, 13 features. Loaded from [jbrownlee/Datasets](https://raw.githubusercontent.com/jbrownlee/Datasets/master/housing.data).
 
## 🤖 Models
 
| Model | Regularization |
|-------|---------------|
| Linear Regression | None |
| Ridge Regression | L2 (alpha=0.1) |
| Lasso Regression | L1 (alpha=0.1) |
 
## 📈 Metrics Used
MSE · RMSE · MAE · R²
 
## 🛠️ Setup
 
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
jupyter notebook Regression_Models_on_Housing_Dataset.ipynb
```
 
## 📜 License
MIT