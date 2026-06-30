# 🏠 Housing Price Prediction using Multiple Linear Regression

## 📌 Project Overview

This project builds a **Multiple Linear Regression** model to predict house prices using various property features such as area, bedrooms, bathrooms, parking, stories, and other amenities. The objective is to identify the key factors affecting house prices and develop an accurate predictive model.

The project follows a complete machine learning workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, evaluation, and interpretation.

---

## 🎯 Objectives

- Identify the factors influencing house prices.
- Build a Multiple Linear Regression model.
- Select the most important features using Recursive Feature Elimination (RFE).
- Evaluate model performance using statistical and machine learning metrics.
- Interpret the effect of each feature on house prices.

---

## 📂 Dataset

The project uses the **Housing.csv** dataset containing **545 residential properties**.

### Features

| Feature | Description |
|----------|-------------|
| price | House price (Target Variable) |
| area | Area of the house |
| bedrooms | Number of bedrooms |
| bathrooms | Number of bathrooms |
| stories | Number of floors |
| mainroad | Connected to main road (Yes/No) |
| guestroom | Guest room available |
| basement | Basement available |
| hotwaterheating | Hot water heating |
| airconditioning | Air conditioning available |
| parking | Parking spaces |
| prefarea | Preferred area |
| furnishingstatus | Furnished / Semi-furnished / Unfurnished |

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

---

## 📊 Project Workflow

### 1. Data Loading

- Load Housing.csv
- Inspect dataset
- Understand data types

### 2. Data Cleaning

- Check missing values
- Handle outliers using the IQR method

### 3. Exploratory Data Analysis (EDA)

- Pair plots
- Box plots
- Correlation heatmap

### 4. Data Preprocessing

- Convert binary categorical variables
- Create dummy variables
- Feature scaling using MinMaxScaler

### 5. Train-Test Split

- 70% Training
- 30% Testing

### 6. Feature Selection

- Recursive Feature Elimination (RFE)

### 7. Model Building

- Multiple Linear Regression
- Ordinary Least Squares (OLS)

### 8. Model Evaluation

- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Residual Analysis
- Variance Inflation Factor (VIF)

---

## 📈 Model Performance

Evaluation metrics include:

- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

Residual analysis was performed to verify the assumptions of linear regression.

---

## 📌 Important Features Selected

The final model selected the following predictors:

- Area
- Bathrooms
- Stories
- Air Conditioning
- Parking
- Preferred Area

---

## 📉 Final Regression Equation

```
Price =
0.35 × Area
+ 0.20 × Bathrooms
+ 0.19 × Stories
+ 0.10 × Air Conditioning
+ 0.10 × Parking
+ 0.11 × Preferred Area
```

> Note: Since Min-Max Scaling was applied, the coefficients represent the effect on the scaled target variable.

---

## 📁 Project Structure

```
Housing-Price-Prediction/
│
├── Housing.csv
├── Housing_Price_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 🚀 Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Housing-Price-Prediction.git
```

Move into the project directory

```bash
cd Housing-Price-Prediction
```

Install the required packages

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```
Housing_Price_Prediction.ipynb
```

---

## 📦 Requirements

```
numpy
pandas
matplotlib
seaborn
scikit-learn
statsmodels
jupyter
```

---

## 📚 Machine Learning Concepts Used

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Dummy Variable Creation
- Min-Max Scaling
- Multiple Linear Regression
- Recursive Feature Elimination (RFE)
- Variance Inflation Factor (VIF)
- Residual Analysis
- Model Evaluation

---

## 📌 Results

The developed Multiple Linear Regression model successfully identifies the most influential factors affecting house prices. Area, number of bathrooms, number of stories, parking availability, air conditioning, and preferred location were found to have the greatest impact on property prices.

The model demonstrates good predictive performance and provides meaningful insights into the housing market.

---

## 👨‍💻 Author

**Your Name**

GitHub: https://github.com/yourusername

---

## 📄 License

This project is licensed under the MIT License.
