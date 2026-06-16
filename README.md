# Customer Shopping Behavior Analysis

## Overview

This project demonstrates an end-to-end Data Analytics workflow using Python, PostgreSQL, and Power BI. The objective was to analyze customer shopping behavior, identify purchasing patterns, and generate actionable business insights through data cleaning, exploration, querying, and visualization.

The project covers:

* Data loading and preprocessing using Python
* Exploratory Data Analysis (EDA)
* Data cleaning and transformation
* SQL analysis using PostgreSQL
* Interactive dashboard development in Power BI
* Business report generation

---

## Dataset

The dataset contains customer shopping information, including demographics, purchase details, product categories, payment methods, and customer preferences.

### Key Features

* Customer ID
* Age
* Gender
* Product Category
* Purchase Amount
* Payment Method
* Subscription Status
* Review Rating
* Frequency of Purchases

---

## Tools & Technologies

| Tool                 | Purpose                             |
| -------------------- | ----------------------------------- |
| Python               | Data cleaning and analysis          |
| Pandas               | Data manipulation                   |
| Matplotlib / Seaborn | Data visualization                  |
| PostgreSQL           | SQL querying and analysis           |
| Power BI             | Dashboard creation                  |
| Git & GitHub         | Version control and project hosting |

---

## Project Workflow

### 1. Data Loading

* Imported dataset into Python.
* Inspected data structure and data types.
* Checked for missing values and inconsistencies.

### 2. Data Cleaning

* Removed duplicates.
* Handled missing values.
* Standardized column names and formats.
* Corrected inconsistent records.

### 3. Exploratory Data Analysis (EDA)

Performed analysis to understand:

* Customer demographics
* Spending behavior
* Product category performance
* Purchase frequency trends
* Subscription patterns
* Customer ratings and satisfaction

### 4. SQL Analysis (PostgreSQL)

Imported the cleaned dataset into PostgreSQL and executed SQL queries to answer business questions such as:

* Top-selling product categories
* Revenue by customer segment
* Average customer spending
* Subscription-based revenue analysis
* Customer purchasing trends

### 5. Dashboard Development

Created an interactive Power BI dashboard featuring:

* Revenue Overview
* Customer Demographics
* Product Category Analysis
* Purchase Trends
* Subscription Insights
* KPI Cards and Filters

---

## Dashboard

### Key Metrics

* Total Revenue
* Total Customers
* Average Purchase Amount
* Subscription Revenue
* Top Product Categories

### Dashboard Features

* Interactive filters
* Dynamic visualizations
* KPI tracking
* Customer behavior insights

*(Add dashboard screenshots here)*

---

## Results & Insights

Some key findings from the analysis include:

* Identified the highest revenue-generating product categories.
* Analyzed spending patterns across different customer groups.
* Compared subscription and non-subscription customer behavior.
* Discovered trends in customer purchasing frequency.
* Generated business recommendations based on customer preferences and purchasing habits.

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/project-name.git
```

### 2. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn psycopg2
```

### 3. Run Python Analysis

```bash
python analysis.py
```

### 4. Load Data into PostgreSQL

* Create a PostgreSQL database.
* Import the cleaned dataset.
* Execute SQL queries from the SQL scripts folder.

### 5. Open Power BI Dashboard

* Open the `.pbix` file in Power BI Desktop.
* Refresh data connections if required.

---

## Project Structure

```text
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
├── notebooks/
│   └── eda.ipynb
├── sql/
│   └── analysis_queries.sql
├── dashboard/
│   └── dashboard.pbix
├── report/
│   └── project_report.pdf
├── screenshots/
│   └── dashboard_images
└── README.md
```

---

## Author

**Your Name**

Aspiring Data Analyst skilled in SQL, Python, PostgreSQL, Power BI, and Data Visualization.
