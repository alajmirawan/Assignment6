# Assignment6
# Ecommerce Customers Analysis & Prediction

## Project Overview

This project applies **Linear Regression** to analyze and predict customer spending using the *Ecommerce Customers* dataset.
The goal is to explore the data, prepare it, and build a predictive model to estimate the **Yearly Amount Spent** by customers.

---

## 📂 Dataset

The dataset used is **Ecommerce Customers**, which includes information such as:

* Avg. Session Length
* Time on App
* Time on Website
* Length of Membership
* Yearly Amount Spent

---

## ⚙️ Steps Performed

### 1. Data Loading

The dataset was loaded into a pandas DataFrame.

### 2. Data Exploration

* Viewed first rows using `head()`
* Checked structure using `info()`
* Generated statistics using `describe()`

### 3. Data Cleaning

* Checked for missing values
* Removed irrelevant categorical columns (e.g., Email, Address, Avatar if present)

### 4. Feature Engineering

* Created a new feature: **Spending per Session**

### 5. Data Preparation

* Defined features (X) and target (y)
* Split data into training and testing sets

### 6. Model Training

* Used **Linear Regression** model from sklearn

### 7. Model Evaluation

* Evaluated using:

  * MAE (Mean Absolute Error)
  * MSE (Mean Squared Error)
  * RMSE (Root Mean Squared Error)

---

## 📊 Results

The model performed well with relatively low error values, indicating a strong ability to predict customer spending.

---

## 📈 Visualization

* Pairplots for feature relationships
* Heatmap for correlations
* Scatter plot (Actual vs Predicted)
* Residual distribution plot

---

## 🧠 Conclusion

The Linear Regression model successfully predicts customer spending based on user behavior.
Key features like **Length of Membership** and **Time on App** show strong influence on spending.
