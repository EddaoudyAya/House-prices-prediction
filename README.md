# 🏠 House Prices Prediction

## 📘 Overview
This project aims to predict the sale prices of residential homes using advanced regression techniques. The analysis includes data exploration, feature engineering, and model development to achieve accurate predictions based on housing attributes.

---

## 📊 Dataset
- **Source:** [Kaggle — House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- **Files Used:**
  - `train.csv` — Training dataset with features and target variable (`SalePrice`)
  - `test.csv` — Test dataset for predictions

The dataset contains **79 explanatory variables** describing various aspects of residential homes in Ames, Iowa.

---

## 🔍 Project Workflow
1. **Data Loading & Exploration**
   - Imported and examined the training and test datasets
   - Analyzed missing values, outliers, and feature distributions  

2. **Feature Engineering**
   - Handled missing values using imputation strategies  
   - Transformed skewed numerical features  
   - Encoded categorical features (label encoding / one-hot encoding)  
   - Created new features where beneficial  

3. **Exploratory Data Analysis (EDA)**
   - Visualized feature relationships with `SalePrice`  
   - Checked correlations between numerical variables  
   - Identified and treated influential outliers  

4. **Modeling**
   - Implemented and evaluated various regression algorithms such as:
     - Linear Regression  
     - Ridge / Lasso Regression  
     - Random Forest Regressor  
     - Gradient Boosting (XGBoost, LightGBM, CatBoost — if applicable)  
   - Used **cross-validation** for model selection and performance evaluation  

5. **Prediction & Submission**
   - Generated predictions for the test set  
   - Prepared a submission file for Kaggle

---

## 📈 Evaluation
Models were evaluated primarily using:
- **Root Mean Squared Log Error (RMSLE)** — the Kaggle competition metric  
- **Cross-validation scores** to assess model generalization  

---

## ⚙️ Installation & Requirements
You can run the notebook locally using the following setup:

```bash
# Clone the repository
git clone https://github.com/yourusername/house-prices-prediction.git
cd house-prices-prediction

# Install dependencies
pip install -r requirements.txt
