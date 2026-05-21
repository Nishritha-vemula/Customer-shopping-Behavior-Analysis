# Customer-shopping-Behavior-Analysis
Data analytics project analyzing customer shopping behavior using Python, SQL, and Power BI to uncover revenue trends, customer segments, purchasing patterns, and business insights.

## Overview

This project focuses on analyzing customer shopping behavior using Python, MySQL, and Power BI. The objective is to transform raw customer data into meaningful business insights by performing data cleaning, exploratory data analysis (EDA), SQL-based analysis, and interactive dashboard creation.

The project demonstrates an end-to-end data analytics workflow from data preprocessing to visualization and business reporting.

---

## Dataset

The dataset contains customer shopping information including:

- Customer ID
- Age
- Gender
- Item Purchased
- Product Category
- Purchase Amount
- Review Rating
- Subscription Status
- Shipping Type
- Discount Information
- Previous Purchases
- Payment Method
- Purchase Frequency

Dataset size:

- Total records: **3900**
- Total features: **18+ attributes**

---

## Tools & Technologies Used

### Programming & Database
- Python
- MySQL

### Python Libraries
- Pandas
- NumPy
- SQLAlchemy
- PyMySQL

### Data Visualization
- Power BI

### Development Environment
- Jupyter Notebook
- VS Code

---

## Project Workflow

### 1. Data Loading

- Imported customer shopping dataset into Python using Pandas.
- Loaded dataset for preprocessing and analysis.

### 2. Data Cleaning

Performed the following cleaning steps:

- Checked for missing values
- Handled null values in review ratings
- Renamed columns for consistency
- Removed redundant columns
- Created new derived features:
  - Age Group
  - Purchase Frequency Days

### 3. Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand:

- Customer demographics
- Purchase behavior
- Product preferences
- Subscription patterns
- Purchase distributions
- Revenue trends

### 4. SQL Analysis in MySQL

Loaded cleaned data into MySQL and executed analytical SQL queries including:

- Revenue by gender
- Subscription spending comparison
- Top-rated products
- Shipping type analysis
- Customer segmentation
- Discount impact analysis
- Revenue contribution by age groups
- Repeat buyer analysis

### 5. Dashboard Development

Created an interactive Power BI dashboard to visualize:

- Total customers
- Average purchase amount
- Average review rating
- Revenue by category
- Sales by category
- Subscription status distribution
- Revenue by age group
- Sales by age group

---

## Dashboard Preview

The Power BI dashboard provides interactive filtering for:

- Subscription Status
- Gender
- Category
- Shipping Type

Key KPI cards include:

- Number of Customers
- Average Purchase Amount
- Average Review Rating

---

## Key Results & Insights

Some insights obtained from the analysis:

- Clothing category generated the highest revenue.
- Young adults contributed the highest sales volume.
- Most customers were non-subscribers.
- Subscription status influenced purchasing patterns.
- Discounts affected purchasing behavior across product categories.
- Repeat customers showed stronger engagement patterns.

---

## Project Structure

```text
customer_behavior_analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_shopping_behavior.csv
├── customer_behavior_sql_queries.sql
├── customer_behavior_dashboard.pbix
├── README.md
└── LICENSE
```

---

## How to Run

### Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/customer_behavior_analysis.git
```

### Step 2: Install Required Libraries

```bash
pip install pandas numpy sqlalchemy pymysql
```

### Step 3: Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Customer_Shopping_Behavior_Analysis.ipynb
```

### Step 4: Run SQL Queries

- Import cleaned data into MySQL
- Execute queries from:

```text
customer_behavior_sql_queries.sql
```

### Step 5: Open Power BI Dashboard

Open:

```text
customer_behavior_dashboard.pbix
```

---

## Future Improvements

- Add predictive analytics models
- Build customer segmentation using machine learning
- Deploy dashboard using cloud services
- Create automated reporting pipelines

---

## Author

Nishrtiha Vemula

LinkedIn:https://www.linkedin.com/in/nishritha-vemula-2159232a6/ 
GitHub: https://github.com/Nishritha-vemula/
