# 🏠 House Price Prediction using Linear Regression

This project predicts the sale prices of houses based on key features such as **square footage**, **number of bedrooms**, and **number of bathrooms** using a **Linear Regression** model.  
The dataset is from the Kaggle competition: [House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

---

## 📌 Project Overview
The goal of this project is to:
- Implement a **Linear Regression model** from scratch using Python & Scikit-learn.
- Use minimal yet relevant features for prediction.
- Prepare a Kaggle submission file.

---

## 📂 Dataset
The dataset contains information about houses in Ames, Iowa, including 79 explanatory variables describing almost every aspect of the homes.

- **Train.csv**: Includes house features and target `SalePrice`.
- **Test.csv**: Includes house features for which predictions are required.

---

## 🛠 Features Used
We have used:
- **GrLivArea** → Above ground living area (square feet)
- **BedroomAbvGr** → Number of bedrooms above ground
- **TotalBathrooms** → Sum of Full Bathrooms + 0.5 × Half Bathrooms

---

## 🚀 Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
pip install -r requirements.txt
