# 🚗 Used Cars Price EDA Project

## 📌 Project Overview

This project performs an Exploratory Data Analysis (EDA) on a dataset containing information about used cars sold across various Indian cities. The goal is to uncover patterns in pricing, understand feature distributions, and explore correlations between variables like fuel type, transmission, owner type, etc.

---

## 📁 Dataset Description

- **File**: `cars.csv`
- **Features** include:
  - **Name** (Car brand and model)
  - **Location** (City of sale)
  - **Year** (Manufacturing year)
  - **Kilometers_Driven**
  - **Fuel_Type**
  - **Transmission**
  - **Owner_Type**
  - **Mileage**
  - **Engine**
  - **Power**
  - **Seats**
  - **New_Price**
  - **Price** (Selling price)

---

## 🎯 Project Goals

- Analyze missing data and handle it appropriately.
- Understand the distribution of key features like price, mileage, power, etc.
- Perform grouping and aggregation for:
  - Fuel type vs average price
  - Location-wise car counts
  - Owner types vs resale value
  - Transmission types vs mileage
- Convert string-based numeric features into actual numeric format.
- Derive insights using `groupby()`, `value_counts()`, and basic visualizations (if applicable).

---

## 🔍 Key Questions Explored

1. What are the most common car models and locations?
2. How are car prices distributed?
3. What’s the average mileage for each transmission type?
4. Which fuel types dominate the market?
5. Which year had the highest number of cars listed?
6. What is the resale value difference by owner type?
7. What is the average power of diesel vs petrol cars?

---

## 🛠️ Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
---

## 📊 Sample Code Tasks

- Handling missing values with `.fillna()`, `.dropna()`
- String cleanup using `.str.replace()` and regex
- Type conversion using `astype()`
- Grouping using `df.groupby()`
- Finding unique counts using `.nunique()` and `.value_counts()`

---

## 🧠 Insights (Optional Summary)

*You may want to fill this based on the final analysis/results in your notebook, e.g.:*

- Diesel cars had higher average power compared to petrol.
- Manual transmission cars were more common, but automatic ones had higher average prices.
- Owner type significantly affects resale price.

---

## ▶️ How to Run

1. Clone or download the repository.
2. Place `cars.csv` in the same folder as the notebook.
3. Open `EDA_Cars_Project_Jasmeet.ipynb` using Jupyter Notebook or VS Code.
4. Run all cells sequentially.

---

## 👤 Author

**Jasmeet Singh Kachle**  
EDA Enthusiast | Python Learner
Mail: sjasmeet7499@gmail.com
