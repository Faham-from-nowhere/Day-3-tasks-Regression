echo "# Day 3: Housing Price Prediction using Linear Regression

## 🎯 Objective
Predict housing prices using various types of Linear Regression models, optimize model performance through data cleaning, feature engineering, regularization, and hyperparameter tuning.

## 🛠️ Tools and Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 📊 Steps Performed
- Data Loading and Cleaning
- Outlier Detection and Removal (IQR method)
- Feature Scaling using StandardScaler
- Model Building:
    - Simple Linear Regression
    - Multiple Linear Regression
    - Optimized Linear Regression (Strong Features Only)
    - Polynomial Regression
    - Ridge Regression
    - Lasso Regression
    - ElasticNet Regression
- Hyperparameter Tuning using GridSearchCV
- Evaluation Metrics: MAE, RMSE, R² Score

## 📈 Model Comparison

| Model | Techniques Used | R² Score | MAE |
|:---|:---|:---|:---|
| Simple Linear Regression | Area vs Price only | ~ | ~ |
| Multiple Linear Regression (All Features) | All raw features | 0.6529 | ₹970,043 |
| Optimized Feature Regression | Only strong features | 0.6226 | ₹1,029,010 |
| Polynomial Regression (Degree 2) | Non-linear features | 0.6216 | ₹1,032,367 |
| Ridge Regression (Scaling + Outlier Removal) | Regularization | 0.6682 | ₹785,110 |
| Lasso Regression (Best Model) | Feature selection + regularization | **0.6684** | **₹784,877** |
| ElasticNet Regression | Hybrid Ridge + Lasso | 0.6636 | ₹790,611 |

## 🏆 Final Conclusion
- Best Model: **Lasso Regression**
- Final R² Score: **0.6684**
- Final MAE: ₹784,877

## 🧠 Learnings
- Outlier removal and scaling improve model quality.
- Regularization (especially Lasso) controls overfitting.
- GridSearch hyperparameter tuning boosts final model performance.

## 📁 Project Structure
Day 3/
├── housing_price_regression.ipynb
├── housing.csv
└── README.md


## ✨ Final Note
This project highlights the power of data preprocessing, feature engineering, and model tuning in building effective machine learning solutions.

" > README.md
