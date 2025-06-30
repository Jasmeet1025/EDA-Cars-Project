# 📊 Used Cars EDA Project

This project is an Exploratory Data Analysis (EDA) on a dataset of used cars sold across India. The goal is to uncover key factors that influence car prices and explore patterns based on location, fuel type, ownership, and more. The entire analysis is performed using Python in Jupyter Notebook, leveraging popular data wrangling and visualization libraries.

---

## 📁 Dataset Description

- **Dataset Name:** Used Cars (India)  
- **Source:** Local file (`cars.csv`)  
- **Size:** Contains thousands of records of car listings  

### Features include:

- **Categorical:** Name, Location, Year, Fuel_Type, Transmission, Owner_Type  
- **Numerical:** Mileage, Power, Kilometers_Driven, Price, New_Price (and others)  

---

## 🛠️ Tools and Libraries Used

- **Pandas:** Data manipulation and analysis  
- **NumPy:** Numerical operations  
- **Matplotlib.pyplot:** Visualization (can be expanded with seaborn or others)  

---

## 🔍 EDA Process Overview

1. **Data Loading:** Loaded the dataset into a DataFrame.  
2. **Initial Inspection:** Checked shape, data types, missing values, and unique counts.  
3. **Data Cleaning:**  
   - Handled missing values in Mileage, Power, Price, and New_Price.  
   - Converted relevant columns to appropriate numeric types after cleaning string formats.  
4. **Exploratory Questions:**  
   - Identified most common car brands and top locations.  
   - Calculated average prices by fuel type, transmission, and year.  
5. **Aggregation & Grouping:**  
   - Grouped data by fuel type, location, owner type, etc.  
   - Computed descriptive statistics such as mean and count.  

---

## 📈 Key Insights

- Diesel cars tend to have higher average power compared to petrol cars.  
- Manual transmission is more common, but automatic cars generally have higher resale prices.  
- Fuel type, manufacturing year, and location significantly influence car prices.  
- Important information was hidden within string-formatted numeric fields like Mileage and Power, requiring data cleaning for proper analysis.  

---

## ▶️ How to Run

```bash
# Clone the repository
git clone https://github.com/Jasmeet1025/used-cars-eda.git

# Navigate to the project directory
cd used-cars-eda

# Launch Jupyter Notebook
jupyter notebook
```
📌 Folder Structure
used-cars-eda/
├── EDA_Cars_Project_Jasmeet.ipynb
├── cars.csv
└── README.md

📬 Contact
Feel free to connect or reach out for feedback, questions, or collaboration!

Jasmeet Singh
📧 sjasmeet7499@gmail.com
🔗 www.linkedin.com/in/jasmeet-singh-kachle-751534289
