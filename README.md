# 🏠 California House Price Prediction

Predict California house prices using Machine Learning and Deep Learning models.

## 📖 Overview

This project predicts the **median house value** of houses in California using demographic and geographical information. Multiple regression algorithms and Artificial Neural Networks (ANNs) are implemented and compared based on their prediction performance.

---

## 📊 Dataset

- California Housing Prices Dataset
- Source: Kaggle
- Target Variable: `median_house_value`

### Features

- Longitude
- Latitude
- Housing Median Age
- Total Rooms
- Total Bedrooms
- Population
- Households
- Median Income
- Ocean Proximity

---

## ⚙️ Data Preprocessing

- Randomly shuffled the dataset
- One-Hot Encoding of `ocean_proximity`
- Removed missing values
- Standardized numerical features
- Split into Training, Validation, and Test datasets

---

## 🤖 Models Used

- Linear Regression
- K-Nearest Neighbors Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- Artificial Neural Network (Simple)
- Artificial Neural Network (Medium)
- Artificial Neural Network (Deep)

---

## 📈 Evaluation Metric

- Root Mean Squared Error (RMSE)

---

## 🛠️ Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib

---

## 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/Ashu2osh0112/California-House-Price-Prediction.git
cd California-House-Price-Prediction
