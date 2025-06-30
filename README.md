# PRODIGY_ML_01
# 🏡 House Price Prediction using Linear Regression

This project implements a Linear Regression model to predict house prices based on features such as square footage, number of bedrooms, and bathrooms. The dataset used is from the popular Kaggle competition "House Prices: Advanced Regression Techniques."

---

## 📦 Dataset

- 🔗 **Dataset Source**: [House Prices - Advanced Regression Techniques | Kaggle](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)

**Key Files:**
- `train.csv`: Training data with features and target (`SalePrice`)
- `test.csv`: Testing data (no `SalePrice`)
- `sample_submission.csv`: Format for submission

---

## ✅ Features Used

For this simplified regression model, we used the following features:
- `GrLivArea`: Ground living area in square feet
- `BedroomAbvGr`: Number of bedrooms above ground
- `FullBath`: Number of full bathrooms

Other preprocessing steps include:
- Handling missing values
- Log transformation of `SalePrice` for better linearity
- Standardization of features using `StandardScaler`

---

## 🧠 Model

- 📈 **Algorithm**: Linear Regression (using scikit-learn)
- 🎯 **Evaluation Metric**: Root Mean Squared Error (RMSE)
- 🧪 **Training RMSE Achieved**: ~31,200

---

## 🛠️ Installation & Setup
Refer to the colab file 

