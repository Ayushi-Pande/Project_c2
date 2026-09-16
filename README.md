# 📊 Superstore Data Analysis & Visualization

## 📌 Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a Superstore dataset using Python.

The main objective is to understand the dataset, identify useful patterns, analyze customer and order information, and visualize important insights using charts and graphs.

---

## 🎯 Objectives

- Understand and explore the Superstore dataset
- Perform data cleaning and basic preprocessing
- Analyze orders based on different categories
- Study customer segments and regions
- Analyze different shipping modes
- Perform numerical analysis using NumPy
- Create meaningful visualizations using Matplotlib
- Extract useful insights from the dataset

---

## 🗂️ Dataset

The dataset used in this project is:

`superstore_excel-selected-columns.csv`

The dataset contains **5,000 records** and includes the following columns:

- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Region
- Category
- Sub-Category

---

## 🛠️ Technologies & Libraries Used

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Jupyter Notebook** – Development environment

---

## 🔍 Analysis Performed

### 1. Dataset Exploration

The dataset was explored using:

- `head()`
- `tail()`
- `shape`
- `columns`
- `dtypes`
- `info()`
- `isnull().sum()`
- `duplicated().sum()`
- `describe()`

### 2. Exploratory Data Analysis

Different aspects of the dataset were analyzed, including:

- Orders by Category
- Orders by Region
- Orders by Customer Segment
- Orders by Ship Mode
- Sub-Category distribution
- Region-wise order analysis
- Category-wise order analysis
- Region and Category relationship

### 3. NumPy Analysis

NumPy was used to analyze shipping duration.

A new column called **Shipping Days** was created using:

`Ship Date - Order Date`

The following numerical measures were calculated:

- Mean
- Median
- Minimum
- Maximum
- Standard Deviation
- Percentage of orders shipped within 3 days

---

## 📈 Visualizations

The project includes visualizations such as:

- 📊 Bar Chart – Orders by Category
- 📊 Bar Chart – Orders by Region
- 🥧 Pie Chart – Orders by Customer Segment
- 🥧 Pie Chart – Orders by Category
- 🥧 Pie Chart – Orders by Region
- 📊 Bar Chart – Orders by Shipping Mode

These visualizations make it easier to understand patterns and distributions within the dataset.

---

## 💡 Key Insights

The analysis helps understand:

- Which categories have the highest number of orders
- Distribution of customers across different segments
- Regional distribution of orders
- Popular shipping modes
- Distribution of products across sub-categories
- Shipping duration patterns

---

## 📁 Project Structure

```text
Superstore_Project/
│
├── project.ipynb
├── superstore_excel-selected-columns.csv
└── README.md
