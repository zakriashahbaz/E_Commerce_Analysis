 # E-Commerce Data Analysis (EDA)

This project performs **Exploratory Data Analysis (EDA)** on an E-commerce dataset to understand sales patterns, customer behavior, and product performance.

The analysis is done using **Python, Pandas, Matplotlib, and Seaborn** in a Jupyter Notebook.

---

## 📂 Project Structure

E_Commerce_Analysis
│
├── E_Commerce_EDA.ipynb      # Main notebook for data analysis
├── E_commerce_data.csv       # Dataset used in the analysis
└── README.md                 # Project documentation

---

## 📊 Objectives

The main goals of this analysis are:

- Understand the structure of the dataset
- Clean and prepare the data
- Analyze sales trends
- Identify top customers
- Find top and lowest selling products
- Analyze revenue by country

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Analysis Steps

### 1. Import Libraries
Required libraries for data analysis and visualization were imported.

### 2. Load Dataset
The dataset was loaded using **Pandas**.

### 3. Dataset Information
Basic information about the dataset was explored:
- Data types
- Missing values
- Statistical summary

### 4. Data Type Conversion
Some columns were converted into appropriate data types (for example `CustomerID`).

### 5. Data Cleaning
Data was cleaned by:
- Removing negative quantities (returned products)
- Removing zero prices

### 6. Feature Engineering
A new column **Revenue** was created:

Revenue = Quantity × UnitPrice

### 7. Monthly Sales Trend
Line chart showing how sales change across months.

### 8. Business Metrics
Important insights were calculated such as:
- Average product revenue
- Product performance

### 9. Top Customers
Bar chart showing the **Top 10 customers by revenue**.

### 10. Lowest Selling Products
Horizontal bar chart of **lowest selling products**.

### 11. Top Selling Products
Horizontal bar chart of **highest selling products**.

### 12. Country Sales
Bar chart showing **top countries by revenue**.

### 13. Product Revenue
Analysis of **top products generating revenue**.

---

## 📈 Key Insights

The analysis helps to identify:

- Which products generate the most revenue
- Which customers contribute the most sales
- Which countries generate the highest revenue
- Monthly trends in sales

---

## ▶ How to Run the Project

1. Clone the repository

```bash
git clone https://github.com/zakriashahbaz/E_Commerce_Analysis.git