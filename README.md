# 🏠 House Price Prediction

**A Machine Learning Model to Predict House Sale Prices Using Key Property Features**

---

## 🚀 Overview

This project applies a **Linear Regression** model to predict the sale prices of houses based on features such as above-ground living area, basement size, number of bathrooms, and bedrooms. It includes both training and prediction functionality, as well as visual comparisons between actual and predicted prices.

Built using **Python**, this project provides an easy way to estimate house prices and visualize performance.

---

## ✨ Features

* 🔍 Predict house prices using **Linear Regression**
* 📊 User input support to predict price of a custom house
* 🖼️ Visualization: Actual vs Predicted prices, feature impact
* 🛠️ Handles missing data using **SimpleImputer**
* 🧪 Tested on both training and test datasets

---

## 🛠️ Tech Stack

* **Language**: Python
* **Libraries**:

  * Pandas, NumPy (Data Handling)
  * Scikit-learn (Model & Preprocessing)
  * Matplotlib, Seaborn (Visualization)

---

## 📁 Dataset

* **train.csv** – contains historical housing data with target `SalePrice`
* **test.csv** – contains similar features for predicting unknown prices

Features used:

* `GrLivArea` – Above Ground Living Area (sq ft)
* `TotalBsmtSF` – Total Basement Area (sq ft)
* `FullBath` – Number of Full Bathrooms
* `HalfBath` – Number of Half Bathrooms
* `BedroomAbvGr` – Bedrooms above ground

---

## 🧪 How It Works

1. **Loads & Preprocesses Data**
   Handles missing values with most frequent imputation.

2. **Trains a Linear Regression Model**
   Learns the relationship between features and `SalePrice`.

3. **Predicts on Training & Test Sets**
   Also allows **interactive prediction** with user input.

4. **Visualizes Results**

   * Actual vs Predicted Sale Prices
   * Impact of `GrLivArea` on price for both train and test data

---

## 📈 Visuals

* **Actual vs Predicted Sale Prices**

<p align="center">
  <img src="assets/actual_vs_predicted.png" alt="Actual vs Predicted" width="500">
</p>

* **GrLivArea vs Predicted Sale Price**

<p align="center">
  <img src="assets/grlivarea_vs_price.png" alt="GrLivArea vs Predicted" width="500">
</p>

---
