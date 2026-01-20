# 📊 Python Data Analysis with Pandas

*Data Technician Bootcamp Project*

This repository showcases a Python data analysis project completed during my **Data Technician bootcamp**. The project focuses on using **pandas** to explore, clean and analyse retail and sales-style datasets, demonstrating practical data handling skills commonly used in entry-level data roles.

The work covers the full data analysis workflow, including creating DataFrames, manipulating and transforming data, handling missing values and producing basic visual insights 📈

---

## 🛠️ Skills and Tools Demonstrated

* Python for data analysis
* pandas for data manipulation and exploration
* Filtering and subsetting data using `.loc[]` and `.iloc[]`
* Data transformation and feature engineering
* Aggregation with `groupby()`
* Sorting with `sort_values()`
* Handling missing data with `isna()`, `dropna()` and `fillna()`
* Data visualisation using pandas built-in plotting and matplotlib

These techniques were applied to **retail-style basket data** and **larger real-world datasets** to simulate common business analysis tasks.

---

## 🧺 Creating a DataFrame from Raw Data

<img width="659" height="333" alt="Screenshot 2026-01-20 122321" src="https://github.com/user-attachments/assets/cf2fcd44-020f-453e-8bdf-56bfc1fac78e" />


This screenshot shows the creation of a pandas DataFrame from a **list of dictionaries** representing a shopping basket. Each dictionary contains item names, quantities and prices. This step demonstrates how raw, unstructured data can be converted into a structured format ready for analysis.

---

## ➕ Data Manipulation and Calculated Columns

<img width="486" height="292" alt="Screenshot 2026-01-20 122449" src="https://github.com/user-attachments/assets/55410e10-d918-4e4d-9a14-cb1e7b65b991" />


Here, a new column is added to the DataFrame by multiplying quantity and price to calculate a **subtotal** for each item. This highlights feature engineering skills and shows how pandas can be used to derive meaningful business metrics from existing data.

---

## 📂 Reading and Exploring CSV Data

<img width="729" height="509" alt="Screenshot 2026-01-20 122549" src="https://github.com/user-attachments/assets/f6bf690e-b372-4db1-9853-960683a3a9cb" />


This screenshot demonstrates loading a larger dataset from a CSV file using `pd.read_csv()`. The dataset is explored by inspecting rows and columns, helping to understand its structure before applying filtering, sorting and further analysis.

---

## 🧹 Identifying Missing Values

<img width="526" height="402" alt="Screenshot 2026-01-20 122755" src="https://github.com/user-attachments/assets/7a5988b2-5e71-4d25-a3cc-4a8090a34443" />


In this example, `.isna().sum()` is used to count missing values across each column. This is a key data cleaning step and was used to decide where to apply `dropna()` or `fillna()` to ensure the dataset was suitable for accurate analysis.

---

## 📈 Visualisation and Analysis

Using pandas plotting and matplotlib, the cleaned datasets were visualised to:

* Compare values across categories
* Identify patterns and trends
* Support insights with clear charts

Visualisation helped turn raw data into understandable outputs that could be communicated clearly to non-technical stakeholders 📊

---

## ✅ Learning Outcomes

Through this project, I developed confidence in:

* Working with pandas DataFrames
* Cleaning and preparing real-world datasets
* Applying analytical thinking to retail and sales data
* Using Python to move from raw data to insight

This project reflects my progression during the Data Technician bootcamp and demonstrates core skills required for junior data and analytics roles 🚀
