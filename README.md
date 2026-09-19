# ☕ Dirty Cafe Sales — Data Cleaning & Analysis with Python

A practical data analytics project by **Kariuki123** demonstrating how to take a messy cafe sales dataset, clean it with Python, explore the data, and extract useful business insights.

The project reflects a real-world analytics workflow:

**Raw Data → Data Cleaning → Exploration → Analysis → Insights**

---

## 📌 Project Overview

Real-world datasets are rarely clean.

This project uses a deliberately messy cafe sales dataset containing issues such as:

- Missing values
- Inconsistent entries
- Incorrect data types
- Invalid values

The goal is to use **Python and Pandas** to transform the raw dataset into reliable and analysis-ready data.

The analysis covers:

- Understanding dataset structure
- Identifying missing and invalid values
- Cleaning and transforming data
- Working with categorical and numerical variables
- Handling dates
- Exploring sales patterns
- Identifying popular products
- Calculating sales metrics
- Extracting business insights

---

## 🎯 Project Objectives

By completing this project, we aim to:

1. Understand the quality of raw sales data.
2. Identify problems that could affect analysis.
3. Clean and standardize the dataset.
4. Perform Exploratory Data Analysis (EDA).
5. Analyze product and sales performance.
6. Communicate findings using Python visualizations.
7. Demonstrate a complete practical data analytics workflow.

---

## 📊 Dataset

The project uses the **Dirty Cafe Sales Dataset**, containing approximately **10,000 café transaction records**.

The dataset includes:

- Transaction ID
- Item
- Quantity
- Price Per Unit
- Total Spent
- Payment Method
- Location
- Transaction Date

The dataset intentionally contains data quality issues, making it ideal for practicing data cleaning techniques.

**Original Dataset:**
Cafe Sales — Dirty Data for Cleaning Training (Kaggle)

---

## 🧹 Data Cleaning

The notebook demonstrates common data-cleaning techniques using Pandas.

Key activities include:

- Inspecting the dataset
- Checking data types
- Identifying missing values
- Identifying duplicate records
- Detecting invalid values
- Converting columns to proper data types
- Handling missing numerical values
- Handling missing categorical values
- Cleaning date columns
- Standardizing inconsistent data
- Creating new analytical columns

The objective is not simply to remove problematic rows, but to understand why the data is problematic and determine the most appropriate treatment.

---

## 🔎 Exploratory Data Analysis

After cleaning the dataset, the project explores several business questions.

### Product Performance

- Which products are sold most frequently?
- Which products generate the most revenue?
- What is the typical quantity purchased?
- How does product performance vary?

### Sales Performance

- What are the overall sales patterns?
- How do sales change over time?
- Which periods record higher or lower sales?

### Customer & Transaction Behaviour

- Which payment methods are most frequently used?
- How do transaction characteristics differ across categories?
- What patterns can be identified from customer transactions?

---

## 📈 Visualizations

The analysis uses Python visualizations to transform data into actionable insights.

Examples include:

- Bar Charts
- Histograms
- Pie Charts
- Line Charts
- Distribution Plots
- Category Comparisons

The focus is on answering business questions rather than creating charts purely for presentation.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|--------|----------|
| Python | Data Analysis |
| Pandas | Data Manipulation & Cleaning |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Analysis Environment |
| Git & GitHub | Version Control & Project Sharing |

---

## 📁 Repository Structure

```text
dirty-cafe-sales/
│
├── Data/
│   └── cafe_sales_dataset.csv
│
├── dirty_cafe_sales_analysis.ipynb
│
└── README.md
```

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Kariuki123/dirty-cafe-sales.git
```

### 2. Navigate into the Project Folder

```bash
cd dirty-cafe-sales
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 5. Open the Notebook

Open:

```text
dirty_cafe_sales_analysis.ipynb
```

Run the notebook cells from top to bottom.


