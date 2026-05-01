# Smart-Retail-Analytics-Total-Spending-Prediction
# 🛍️ Retail Sales Analysis & Spending Prediction

## 📌 Overview

This project focuses on analyzing a retail transactions dataset and building a machine learning model to predict customer spending (**TotalSpent**).

The project covers the full data science pipeline including data cleaning, exploratory data analysis (EDA), feature engineering, and predictive modeling.

---

## 📊 Dataset Description

The dataset contains retail transaction records with the following features:

* Transaction ID
* Item
* Quantity
* Price per Unit
* Total Spent
* Payment Method
* Location
* Transaction Date

---

## ⚙️ Project Workflow

### 1. Data Cleaning & Preprocessing

* Handled missing values
* Removed duplicates
* Fixed invalid entries (e.g., "ERROR", "UNKNOWN")
* Converted data types
* Treated outliers using IQR
* Imputed missing values using statistical methods

---

### 2. Exploratory Data Analysis (EDA)

Key insights explored:

* Top selling items
* Payment method distribution
* Location-based transaction analysis
* Distribution of Quantity, Price, and TotalSpent
* Correlation between features

---

### 3. Feature Engineering

* Created new features from date (day, month, weekday)
* Generated interaction feature:
  `Quantity × Price_Per_Unit`

---

### 4. Machine Learning Model

* Model Used: **Linear Regression**
* Preprocessing:

  * StandardScaler (numerical features)
  * OneHotEncoder (categorical features)

---

## 📈 Model Performance

| Metric | Value |
| ------ | ----- |
| MAE    | 0.578 |
| RMSE   | 1.8   |
| R²     | 0.90  |

✔ High R² indicates strong predictive performance
✔ Low MAE/RMSE indicates low prediction error

---

## 📉 Model Evaluation

* Predicted vs Actual plot shows good alignment
* Residuals are randomly distributed → model is reasonably well-fitted

---

## 🧠 Key Insights

* Strong positive relationship between **Quantity** and **TotalSpent**
* Customer payment preferences vary significantly
* Certain items dominate sales frequency
* TotalSpent depends mainly on Quantity and Price

---

## ⚠️ Limitations

* Model performance depends on dataset quality
* Linear Regression may not capture non-linear relationships
* Results are based on a single train/test split

---

## 🚀 Future Improvements

* Try advanced models (Random Forest, XGBoost)
* Apply cross-validation
* Add more features
* Improve handling of categorical variables

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn




⭐ If you found this project useful, consider giving it a star!

