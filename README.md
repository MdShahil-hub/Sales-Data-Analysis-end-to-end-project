# 📊 Sales Data Analysis & Dashboard | Python, MySQL & Power BI

## 📌 Project Overview

An end-to-end Sales Data Analysis project using Python, MySQL, and Power BI to clean sales data, perform data transformations, store the cleaned data in a MySQL database, and build an interactive dashboard to analyse sales and profit performance.

The project uses an Excel dataset containing 520 rows and 7 columns.

## 🛠️ Tools & Technologies

- Python
- Pandas
- Jupyter Notebook
- MySQL
- SQLAlchemy & PyMySQL
- Microsoft Power BI
- Excel & CSV

## 📊 Key Performance Indicators (KPIs)

- **Total Sales:** Sales performance across the dataset
- **Total Profit:** Profit generated from sales
- **Average of Percent:** Percentage metric displayed on the dashboard

## 📈 Dashboard Features

- Monthly sales analysis
- Region-wise profit comparison
- Product-wise sales analysis
- Region slicer for interactive filtering
- Year slicer for time-based filtering
- KPI cards for sales, profit, and percentage

## 🧹 Data Cleaning & Preparation

- Initial dataset contained 520 rows and 7 columns.
- Identified 20 duplicate rows.
- Removed duplicate records.
- Removed rows containing null values in `Order_Date`.
- Created a `Year` column from `Order_Date`.
- Created a `Month` column from `Order_Date`.
- Created a `Profit` column using `Sales - Cost`.
- Exported the cleaned dataset to CSV format.
- Stored the cleaned data in MySQL using Python, SQLAlchemy, and PyMySQL.
- Connected Power BI to MySQL to build the dashboard.

## 🔍 Key Insights

- Monthly sales charts help analyse sales trends over time.
- Regional profit analysis compares performance across East, North, South, and West.
- Product-wise sales analysis compares Printer, Tablet, Laptop, Monitor, and Mobile.
- Region and Year slicers allow users to explore sales and profit under different filter selections.

*Note: Numerical findings can be added after validating the dashboard values. Results may change when filters are applied.*

## 🖼️ Dashboard Preview

![Sales Dashboard](dashboard.pdf)

## 🚀 How to Use

1. Clone or download this repository.
2. Open the Jupyter Notebook and run the EDA and data-cleaning steps.
3. Export the cleaned dataset to CSV.
4. Create or use the `keepsales` database in MySQL.
5. Connect Python to MySQL using SQLAlchemy and PyMySQL.
6. Load the cleaned data into a MySQL table.
7. Connect Power BI Desktop to MySQL.
8. Open the dashboard and use the Region and Year slicers to explore the data.

## 🎯 Project Objective

To demonstrate practical skills in exploratory data analysis, data cleaning with Python, MySQL database integration, and interactive dashboard development using Power BI.

## 👤 Author

**Mohammad Shahil Khan**

Aspiring Data Analyst
