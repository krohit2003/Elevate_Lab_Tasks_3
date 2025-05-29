# Elevate_Lab_Tasks_3
INTERN AT ELEVATE LABS TASKS


# 🏡 Housing Price Prediction using Linear Regression

This repository contains a machine learning project that uses **Linear Regression** to predict house prices based on various numerical and categorical features provided in the `Housing.csv` dataset.

---

## 📂 Dataset Description

The dataset includes the following features:

- `area`: Area of the house
- `bedrooms`, `bathrooms`, `stories`, `parking`: Numerical features
- Categorical features like:
  - `mainroad`, `guestroom`, `basement`, `hotwaterheating`, `airconditioning`, `prefarea`, `furnishingstatus`
- `price`: Target variable (house price)

---

## 🚀 Project Workflow

### 1. Data Loading & Inspection
- Loaded the housing dataset using `pandas`.
- Viewed basic structure and content of the dataset.

### 2. Data Preprocessing
- Applied **one-hot encoding** to categorical columns using `pd.get_dummies()`, with `drop_first=True` to avoid multicollinearity.

### 3. Train-Test Split
- Split data into training and testing sets using `train_test_split()` from `sklearn`.

### 4. Feature Scaling
- Used `StandardScaler` to **standardize features** (mean = 0, std = 1), which improves model performance.

### 5. Model Training
- Trained a **Linear Regression** model using scaled features from training data.

### 6. Evaluation
- Predicted house prices on test data.
- Calculated:
  - Mean Absolute Error (MAE)
  - Mean Squared Error (MSE)
  - R² Score (R-squared)
- Extracted model coefficients to interpret feature importance.

### 7. Visualization
- Created a scatter plot of **Actual vs Predicted** prices to visually assess model accuracy.

---

## 📊 Results

- Evaluated model accuracy using standard regression metrics.
- Found top contributing features to price prediction.
- Visualized model performance.

---

## 🛠️ Libraries Used

- Python 3
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

---


