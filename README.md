📊 Used Cars EDA Project
This project is an Exploratory Data Analysis (EDA) on a dataset of used cars sold across India. The aim is to understand key factors affecting car prices and explore patterns based on location, fuel type, ownership, and more.
The entire analysis was done using Python in Jupyter Notebook, utilizing popular data wrangling libraries.

📁 Dataset Description
Dataset Name: Used Cars (India)

Source: Local file (cars.csv)

Size: Contains thousands of records of car listings

Features:

Name, Location, Year, Fuel_Type, Transmission, Owner_Type

Numeric columns like Mileage, Power, Kilometers_Driven, Price, etc.

Mix of categorical and numerical features

🛠️ Tools and Libraries Used
Pandas – for data manipulation and analysis

NumPy – for numerical operations

Matplotlib.pyplot
(Visualization libraries can be added here if used later)

🔍 EDA Process Overview
Data Loading

Initial Inspection

Viewed shape, datatypes, null counts, unique values

Data Cleaning

Handled missing values in Mileage, Power, Price, and New_Price

Converted columns to appropriate numeric formats

Exploratory Questions

Identified most common car brands, top locations

Found average prices by fuel type, transmission, and year

Aggregation & Grouping

Grouped data by fuel type, location, owner type, etc.

Calculated mean, count, and other descriptive stats

📈 Key Insights
Diesel cars had higher average power compared to petrol.

Manual transmission was more common, but automatic cars were more expensive.

Fuel type, year, and location significantly influence the resale price.

A lot of useful information was hidden in string-formatted numeric fields like Mileage and Power.

▶️ How to Run

Clone the repository:
git clone https://github.com/Jasmeet1025/used-cars-eda.git

Navigate into the project folder and run the notebook:
cd used-cars-eda
jupyter notebook

Make sure cars.csv is in the same directory as the notebook. If it's not, adjust the file path inside the notebook.

📌 Folder Structure
used-cars-eda/
├── EDA_Cars_Project_Jasmeet.ipynb
├── cars.csv
└── README.md
📬 Contact
Feel free to connect or reach out for feedback or collaboration!

Jasmeet Singh
📧 sjasmeet7499@gmail.com
🔗 LinkedIn Profile
www.linkedin.com/in/jasmeet-singh-kachle-751534289
