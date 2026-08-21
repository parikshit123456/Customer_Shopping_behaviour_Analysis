# Customer Shopping Behavior Analysis

<img width="917" height="614" alt="image" src="https://github.com/user-attachments/assets/0a8b1348-2902-40ae-ada5-08a909be2007" />

## Overview

This project analyzes customer shopping behavior to identify trends, understand purchasing patterns, and generate actionable business insights. The analysis focuses on factors such as customer demographics, product categories, discounts, reviews, seasons, payment methods, and purchase behavior.

The goal is to help the business improve customer engagement, optimize marketing strategies, enhance product decisions, and support data-driven decision-making.

---

## Dataset

The dataset contains customer shopping and purchase-related information used to analyze consumer behavior and identify key business trends.

Key areas analyzed include:

* Customer demographics
* Product categories
* Purchase amounts
* Discounts applied
* Review ratings
* Seasonal purchasing patterns
* Payment methods
* Subscription and loyalty status
* Online and offline purchasing behavior
* Repeat purchase patterns

---

## Tools & Technologies

* **Python** – Data loading, cleaning, transformation, and exploratory data analysis
* **Pandas & NumPy** – Data manipulation and analysis
* **Matplotlib / Seaborn** – Data visualization
* **MySQL / SQL Server** – SQL-based business analysis
* **Power BI** – Interactive dashboard development
* **Gamma** – Presentation creation
* **Microsoft PowerPoint** – Final project presentation
* **GitHub** – Project documentation and version control

---

## Project Steps

### 1. Data Loading

The dataset was imported into Python using Pandas for initial exploration and analysis.

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand:

* Dataset structure
* Data types
* Missing values
* Customer and purchasing patterns
* Distribution of important variables
* Relationships between different features

### 3. Data Cleaning

The dataset was cleaned and prepared for analysis by:

* Handling missing values
* Removing or checking duplicate records
* Correcting data types
* Standardizing column names
* Preparing the dataset for SQL and visualization tools

### 4. SQL Analysis

The cleaned dataset was analyzed using **MySQL / SQL Server**.

Business-focused SQL queries were used to answer questions related to:

* Customer segmentation
* Top-performing products and categories
* Discount usage
* Purchase behavior
* Customer loyalty
* Sales trends
* Payment preferences
* Seasonal patterns
* Repeat customers and purchase drivers

### 5. Power BI Dashboard

An interactive Power BI dashboard was created to visualize important KPIs and business insights.

The dashboard includes visualizations for:

* Total customers
* Total sales and purchase amounts
* Product category performance
* Customer demographics
* Discount analysis
* Subscription and loyalty behavior
* Seasonal purchasing trends
* Payment method preferences
* Customer purchase patterns

### 6. Report Creation

A detailed project report was prepared to document:

* Business problem
* Project objectives
* Dataset overview
* Data cleaning process
* SQL analysis
* Dashboard insights
* Key findings
* Business recommendations

### 7. Presentation

A professional project presentation was created using **Gamma** to communicate the analysis, insights, and recommendations in a clear and visually engaging format.

---

## Dashboard

The Power BI dashboard provides an interactive overview of customer shopping behavior and allows stakeholders to explore key business trends.

Example insights include:

* Which customer groups contribute the most to purchases
* Which product categories perform best
* How discounts influence purchasing behavior
* Seasonal changes in customer demand
* Popular payment methods
* Customer loyalty and subscription patterns

---

## Results & Key Insights

The analysis helps identify meaningful patterns in customer shopping behavior and provides insights that can support better business decisions.

Key outcomes include:

* Identification of high-performing product categories
* Understanding of customer purchasing preferences
* Analysis of discount usage and its impact on purchases
* Identification of valuable customer segments
* Insights into loyalty and repeat purchasing behavior
* Understanding of seasonal and demographic trends

These insights can help the company improve **marketing campaigns, customer engagement, product strategy, and overall sales performance**.

---

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── python/
│   ├── data_cleaning.py
│   └── eda.py
│
├── sql/
│   ├── mysql_queries.sql
│   └── sql_server_queries.sql
│
├── powerbi/
│   └── Customer_Shopping_Dashboard.pbix
│
├── report/
│   └── Project_Report.pdf
│
├── presentation/
│   └── Project_Presentation.pptx
│
└── README.md
```

---

## How to Run

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd Customer-Shopping-Behavior-Analysis
```

### 2. Install Python Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Run the Python Analysis

```bash
python data_cleaning.py
python eda.py
```

### 4. Run SQL Queries

* Import the cleaned dataset into **MySQL** or **SQL Server**
* Open the SQL query files from the `sql/` folder
* Execute the queries to generate business insights

### 5. Open the Power BI Dashboard

Open the `.pbix` file using **Power BI Desktop**.

---

## Business Objective

The main business question addressed in this project is:

> **How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?**

This project demonstrates an end-to-end data analytics workflow, from raw data preparation to SQL analysis, dashboard development, reporting, and presentation.

---

## Author

**Parikshit Mandal**
BCA Final Year Student | Aspiring Data Analyst

⭐ If you found this project useful, consider giving the repository a star!
