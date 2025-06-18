# 🚗 Predicting MPG (Miles Per Gallon) Using Regression

This project aims to build and evaluate machine learning regression models to predict the **Miles Per Gallon (MPG)** of automobiles based on various features from the UCI Auto MPG dataset. This type of predictive modeling is useful for estimating fuel efficiency based on car specifications.

---

## 📌 Problem Statement

Fuel efficiency (MPG) is an important metric in automobile performance and environmental impact. Given a dataset of cars with attributes like horsepower, weight, acceleration, etc., the goal is to **predict the MPG** using various regression models.

---

## 📂 Dataset

The dataset used is the **Auto MPG dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/auto+mpg). It contains the following columns:

| Feature         | Description                          |
|-----------------|--------------------------------------|
| `mpg`           | Miles per gallon (target variable)   |
| `cylinders`     | Number of cylinders in the car       |
| `displacement`  | Engine displacement (cubic inches)   |
| `horsepower`    | Engine horsepower                    |
| `weight`        | Vehicle weight                       |
| `acceleration`  | Time to accelerate from 0 to 60 mph  |
| `model year`    | Model year of the car                |
| `origin`        | Region of origin (1=USA, 2=Europe…)  |
| `car name`      | Car model name (often dropped)       |

---

## ⚙️ Technologies and Libraries Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn (`sklearn`)
- XGBoost
- Jupyter Notebook

---

## 🔍 Approach

1. **Data Cleaning**
   - Handle missing values (e.g., horsepower)
   - Convert categorical features (`origin`) if needed

2. **Exploratory Data Analysis (EDA)**
   - Correlation matrix
   - Pair plots
   - Feature distribution plots

3. **Feature Engineering**
   - Normalization/Standardization
   - Encoding categorical variables

4. **Model Building**
   - Linear Regression
   - Decision Tree Regressor
   - Random Forest Regressor
   - XGBoost Regressor

5. **Model Evaluation**
   - Metrics: MAE, MSE, RMSE, R² Score
   - Residual Analysis
   - Visualization of predictions vs actuals

---

## 📈 Results

| Model                  | R² Score | RMSE   | MAE    |
|------------------------|----------|--------|--------|
| Linear Regression      | 0.75     | 3.15   | 2.30   |
| Decision Tree Regressor| 0.85     | 2.15   | 1.65   |
| Random Forest Regressor| 0.88     | 1.92   | 1.43   |
| XGBoost Regressor      | 0.90     | 1.78   | 1.29   |
