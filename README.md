# 🏡 House Price Prediction Using Linear Regression

## 📌 Project Objective
Build a linear regression model to predict house prices using:
- House Size (in square feet)
- Location (Urban, Suburban, Rural)
- Number of Rooms

## 🧪 Tools & Technologies
- Python, Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (LinearRegression, train_test_split, StandardScaler)

## 🔍 Key Steps
1. Data Cleaning & Preprocessing
2. Visualizations (Distributions, Correlation, Outliers)
3. Feature Scaling & One-Hot Encoding
4. Linear Regression Modeling
5. Model Evaluation (RMSE, R² Score)
6. Feature Importance Analysis

## 📈 Results
- **RMSE**: 24,000 (example)
- **R² Score**: 0.86 (example)
- Strong positive correlation between Size and Price.
- Urban locations significantly increase price.

## 📂 File Structure
- `house_price_prediction.ipynb`: Main notebook
- `data/house_prices.csv`: Sample dataset
- `README.md`: Project overview

## 🚀 Run Locally
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
jupyter notebook house_price_prediction.ipynb
