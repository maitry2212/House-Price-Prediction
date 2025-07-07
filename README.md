# 🏡 House Price Prediction Using Linear Regression

This project uses **Linear Regression** to predict house prices based on various housing features.  
It demonstrates a full machine learning workflow — from loading data and exploration to model training and evaluation.

---

## 🚀 Overview
- **Dataset:** Boston Housing (506 samples, 13 features)
- **Goal:** Predict median house value (`MEDV`)
- **Tech Stack:** Python, Pandas, Scikit-learn, Matplotlib, Seaborn

---

## 📊 Features
Some key features used from the dataset:
- `CRIM` - per capita crime rate by town
- `ZN` - proportion of residential land zoned for large lots
- `INDUS` - proportion of non-retail business acres
- `RM` - average number of rooms per dwelling
- `LSTAT` - % lower status of the population
- *(and more...)*

---

## ⚙️ How to Run

## 1️⃣ Clone this repository
```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction

Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

3️⃣ Run the notebook
Open House_Price_Prediction.ipynb in Jupyter or upload it to Google Colab.

📈 Results
✅ Model Evaluation
Mean Squared Error: 24.29
R² Score: 0.67

📉 Actual vs Predicted Plot
This plot shows how well our model predicts the house prices.
The closer the points are to the red diagonal line, the better the predictions.
