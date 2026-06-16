# 📊 Customer Shopping Behavior Analysis

## 📌 Overview

This project focuses on analyzing customer shopping behavior using a retail transaction dataset containing 3,900 customer purchase records. The objective was to transform raw data into actionable business insights through data cleaning, exploratory data analysis (EDA), SQL-based analysis, interactive dashboarding, and business reporting.

The project demonstrates an end-to-end Data Analytics workflow using Python, PostgreSQL, Power BI, and Gamma.

---

## 📂 Dataset

The dataset contains customer demographics, purchase information, shopping preferences, and customer engagement metrics.

### Dataset Summary

* **Rows:** 3,900
* **Columns:** 18

### Key Features

* Age
* Gender
* Location
* Subscription Status
* Item Purchased
* Product Category
* Purchase Amount
* Season
* Size
* Color
* Review Rating
* Shipping Type
* Discount Applied
* Previous Purchases
* Purchase Frequency

---

## 🛠 Tools & Technologies

| Tool                 | Purpose               |
| -------------------- | --------------------- |
| Python               | Data Cleaning & EDA   |
| Pandas               | Data Manipulation     |
| NumPy                | Numerical Operations  |
| Matplotlib & Seaborn | Data Visualization    |
| PostgreSQL           | SQL Analysis          |
| Power BI             | Dashboard Development |
| Gamma                | Presentation Creation |
| GitHub               | Project Documentation |

---

## 🔄 Project Workflow

### 1️⃣ Data Loading

* Imported dataset using Pandas.
* Inspected data structure and column information.
* Generated summary statistics.

### 2️⃣ Data Cleaning

* Identified missing values.
* Imputed missing review ratings using category-wise median values.
* Standardized column names using snake_case.
* Removed redundant fields.
* Validated data consistency.

### 3️⃣ Feature Engineering

Created additional features to improve analysis:

* Age Group Classification
* Purchase Frequency Metrics
* Customer Segmentation Features

### 4️⃣ Exploratory Data Analysis (EDA)

Performed visual and statistical analysis to understand:

* Customer demographics
* Spending patterns
* Product category performance
* Review ratings
* Subscription behavior
* Shipping preferences

### 5️⃣ PostgreSQL Analysis

Loaded cleaned data into PostgreSQL and executed business-focused SQL queries.

#### Business Questions Answered

* Revenue by Gender
* Subscribers vs Non-Subscribers
* Revenue by Age Group
* Top Rated Products
* Top Products by Category
* High-Spending Discount Users
* Shipping Type Comparison
* Repeat Buyer Analysis
* Customer Segmentation
* Discount Dependency Analysis

### 6️⃣ Power BI Dashboard

Designed an interactive dashboard to visualize business insights.

#### Dashboard Features

* KPI Cards
* Revenue Analysis
* Sales Analysis
* Customer Segmentation
* Subscription Insights
* Interactive Filters
* Category Performance Analysis

### Dashboard KPIs

| KPI                     | Value  |
| ----------------------- | ------ |
| Customers               | 3.9K   |
| Average Purchase Amount | $59.76 |
| Average Review Rating   | 3.75   |

---

## 📈 Key Insights

### Customer Subscription

* 73% of customers are non-subscribers.
* 27% are subscribers.

### Product Performance

* Clothing generated the highest revenue and sales.
* Accessories ranked second in overall performance.
* Footwear and Outerwear showed lower sales contribution.

### Customer Segments

* Young Adults generated the highest revenue.
* Young Adults also recorded the highest number of purchases.

### Sales Performance

* Clothing:

  * Revenue: 104K
  * Sales: 1,737

* Accessories:

  * Revenue: 74K
  * Sales: 1,240

---

## 💡 Business Recommendations

* Increase subscription adoption through loyalty programs.
* Focus marketing campaigns on high-value customer segments.
* Promote top-rated products.
* Optimize discount strategies to maintain profitability.
* Encourage repeat purchases through personalized offers.

---

## 📊 Deliverables

* Python Data Cleaning Notebook
* EDA Visualizations
* PostgreSQL SQL Scripts
* Power BI Dashboard
* Business Analysis Report
* Gamma Presentation (PPT)

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

### Run Jupyter Notebook

```bash
jupyter notebook
```

### Connect to PostgreSQL

Update database credentials inside the notebook and execute the SQL scripts.

### Open Power BI Dashboard

Open the `.pbix` file using Power BI Desktop.

---

## 📷 Dashboard Preview


