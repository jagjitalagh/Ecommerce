# 🛒 E-commerce Data Analysis with Python & MySQL

This project demonstrates how to build and analyze an E-commerce dataset using Python for data handling and MySQL for storage and queries. It involves importing CSV data, performing SQL operations, and visualizing insights.

## 🚀 Features

- Automated ingestion of CSV files into MySQL tables
- Data cleaning and transformation using Pandas
- SQL-based business insights queries
- Visualizations using Seaborn and Matplotlib

## 📂 Dataset

The project uses multiple CSV files:
- `customers.csv`
- `orders.csv`
- `order_items.csv`
- `products.csv`
- `payments.csv`
- `sellers.csv`
- `geolocation.csv`

## 🛠️ Technologies Used

- Python 3
- MySQL
- Pandas
- Seaborn
- Matplotlib
- MySQL Connector

## 📦 Setup Instructions

1. Clone the repository and install dependencies:
    ```jupyter notebook
    !pip install pandas matplotlib seaborn mysql-connector-python
    ```

2. Ensure MySQL server is running and create a database:
    ```sql
    CREATE DATABASE ecommerce;
    ```

3. Place all CSV files in the specified directory (e.g., `D:\Ecommerce`).

4. Run the notebook to create tables and populate them.

## 📊 Visualizations & Insights

The notebook includes:
- Distribution of customers across cities
- Seller performance analysis
- Product category trends
- Payment type breakdown

