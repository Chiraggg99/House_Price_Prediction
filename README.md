# 🏡 House Price Prediction using XGBoost

## 📌 Overview
A machine learning model utilizing XGBoost to estimate house prices based on various property-related features. The goal is to create a regression model that accurately estimates house prices from input variables.

---

## 📊 Dataset
The dataset contains the following key attributes affecting house prices:

- 🏠 **Lot Size**  
- 🛏️ **Number of Bedrooms**  
- 🛁 **Number of Bathrooms**  
- 📐 **Square Footage**  
- 🏗️ **Year Built**  
- 🌆 **Location & Neighborhood Features**  
- 📈 **Market Trends**

## 🧠 Model & Approach

### 🔧 Preprocessing
- Missing values handled using imputation.
- Categorical features encoded using One-Hot Encoding.
- Numerical features scaled using StandardScaler (if needed).

### 🤖 Model
- Algorithm: **XGBoost Regressor**
- Optional: Hyperparameter tuning via GridSearchCV or RandomizedSearchCV

### 📏 Evaluation Metrics
- ✅ **RMSE** (Root Mean Square Error)  
- ✅ **MAE** (Mean Absolute Error)  
- ✅ **R² Score**

---

## ⚙️ Installation & Requirements

Install the necessary dependencies using pip:

```bash
pip install numpy pandas scikit-learn xgboost matplotlib seaborn

