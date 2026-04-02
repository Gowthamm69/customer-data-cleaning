# Customer Data Cleaning and Preprocessing

## 📌 Overview
This project demonstrates how to clean and preprocess raw customer data for machine learning.

## ⚙️ Tasks Performed
1. Handling missing values:
   - Age → filled with median
   - City → filled with mode
2. Removed duplicate records
3. Encoding:
   - One-hot encoding for city
   - Label encoding for gender
4. Feature Scaling:
   - Min-Max Scaling
   - Standardization

## 📊 Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn

## 📈 Scaling Explanation
Min-Max scaling is used when features need to be in a fixed range (0–1), especially for distance-based models.  
Standardization is used when data follows a normal distribution or when models require centered data.

## 🚀 How to Run
1. Install dependencies:
