
# 🏠 Regression House Price Estimation

This project implements a regression model to estimate house prices based on various features such as square footage, number of bedrooms/bathrooms, zip code, and more. The approach follows a structured machine learning workflow using pandas, NumPy, and scikit-learn.

---

## 📌 Project Overview

The goal of this project is to build a regression model that can predict house prices with a reasonable degree of accuracy. The dataset used contains multiple numerical and categorical features relevant to real estate valuation.

---

## 💻 Environment

- Platform: Google Colab
- Language: Python
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

---

## 📁 Dataset Information

- Contains features like:
  - Square footage
  - Number of bedrooms
  - Bathrooms
  - Zip code
  - Price (target variable)

---

## 🧪 Key Steps

1. **Importing Libraries**
   - pandas, numpy, seaborn, matplotlib, scikit-learn

2. **Loading Dataset**
   - CSV file is loaded into a pandas DataFrame.

3. **Data Cleaning**
   - Missing values handled
   - Outliers removed
   - Zip codes with less than 25 data points were removed using `inplace=True`.

4. **Exploratory Data Analysis (EDA)**
   - Visualized correlation matrix using heatmaps
   - Distribution plots of features
   - Box plots and scatter plots

5. **Feature Selection & Engineering**
   - Dropped irrelevant columns
   - One-hot encoding for categorical variables (e.g., zip code)
   - Split dataset into training and testing sets using `train_test_split`

6. **Model Building**
   - Linear Regression using `LinearRegression()` from scikit-learn

7. **Model Evaluation**
   - Evaluated using metrics like:
     - R² Score
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Upload the dataset CSV file
3. Run cells sequentially to:
   - Clean data
   - Visualize insights
   - Train and evaluate the model

---

## 🧠 Key Learnings

- Understanding of data preprocessing for regression tasks
- Insights on feature engineering and handling outliers
- Application of linear regression in housing datasets

---

## 📦 Requirements

Make sure the following packages are installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🔚 Conclusion

This project demonstrates how linear regression can be applied to real-world datasets to make meaningful predictions. With additional tuning and model enhancements, the accuracy of predictions can be improved for deployment scenarios.
