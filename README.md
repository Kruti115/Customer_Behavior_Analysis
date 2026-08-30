# 📊 Customer Behavior Analysis

An end-to-end data analytics project that analyzes customer shopping behavior to identify purchasing patterns, customer segments, product performance, and business opportunities using **Python, PostgreSQL, SQL, and Power BI**.


## 📌 Project Overview

Understanding customer purchasing behavior is essential for improving customer retention, optimizing product strategies, and making data-driven business decisions.

This project analyzes a customer shopping behavior dataset containing demographic information, purchasing history, product details, transaction information, discounts, subscriptions, and customer preferences.

The project follows an end-to-end analytics workflow:

**Data Cleaning → Exploratory Data Analysis → SQL Analysis → Power BI Dashboard → Business Insights**


## 🎯 Objectives

The main objectives of this project are to:

* Analyze customer purchasing patterns
* Identify high-value customer segments
* Understand product and category performance
* Analyze the impact of discounts and promotional offers
* Compare subscribed and non-subscribed customers
* Identify seasonal purchasing trends
* Analyze customer purchase frequency
* Build an interactive business intelligence dashboard
* Generate actionable business recommendations


## 📂 Dataset
**Dataset:** Customer Shopping Behavior Dataset

**Size:**

* 3,900 records
* 18 columns

### Key Attributes

| Category          | Attributes                                                      |
| ----------------- | --------------------------------------------------------------- |
| Customer          | Customer ID, Age, Gender, Location                              |
| Product           | Item Purchased, Category, Size, Color, Season                   |
| Transaction       | Purchase Amount, Review Rating                                  |
| Marketing         | Discount Applied, Promo Code Used                               |
| Customer Behavior | Subscription Status, Previous Purchases, Frequency of Purchases |
| Operations        | Shipping Type, Payment Method                                   |


## 🛠️ Technologies Used

### Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

### Database & SQL

* PostgreSQL
* SQL

### Visualization

* Microsoft Power BI
* DAX

### Other Tools

* Git
* GitHub


## 🔄 Project Workflow

### 1. Data Loading

The dataset was loaded into Python using Pandas.

Initial checks were performed to understand:

* Dataset dimensions
* Column names
* Data types
* Missing values
* Duplicate records
* Data consistency

### 2. Data Cleaning

The dataset was prepared for analysis by:

* Checking missing values
* Removing duplicate records
* Standardizing categorical values
* Correcting data types
* Preparing analytical fields

### 3. Exploratory Data Analysis

EDA was performed to understand:

* Customer demographics
* Purchase amount distribution
* Product category performance
* Seasonal purchasing behavior
* Customer purchasing frequency
* Subscription behavior
* Discount and promotional impact

### 4. SQL Analysis

The cleaned dataset was loaded into PostgreSQL for structured analytical querying.

The SQL analysis investigates areas such as:

* Revenue by category
* Average purchase amount
* Customer purchasing frequency
* Subscription vs. non-subscription behavior
* Discount impact
* Promotional code usage
* Customer segmentation

### 5. Power BI Dashboard

An interactive Power BI dashboard was created to provide a business-oriented view of the analysis.
## 📸 Dashboard Preview

### Dashboard Overview
![Customer Behavior Dashboard](screenshots/dashboard_overview.png)

### Interactive Filtered Analysis
![Filtered Customer Behavior Analysis](screenshots/dashboard_filtered_analysis.png)

### Dashboard includes:

* Total Revenue
* Average Order Value
* Product Category Performance
* Top-Selling Products
* Customer Segments
* Subscription Analysis
* Seasonal Trends
* Demographic Analysis
* Interactive filters and slicers

### Key Metrics

- Total Customers
- Average Purchase Amount
- Average Review Rating

### Analysis Areas

- Subscription behavior
- Revenue by category
- Sales by category
- Revenue by age group
- Sales by age group
- Customer demographics
- Shipping preferences

### Filters

The dashboard allows users to dynamically filter the analysis by:

- Subscription Status
- Gender
- Category
- Shipping Type


## 📈 Key Insights

The analysis identified several important customer behavior patterns:

* High-performing product categories and seasons were identified.
* Customer purchasing frequency varies significantly across customer segments.
* Subscription status provides useful insight into differences in customer behavior.
* Discounts and promotional offers can be analyzed in relation to purchase behavior.
* Certain customer segments demonstrate higher purchase frequency and transaction value.


## 💡 Business Recommendations

Based on the analysis, businesses could:

1. Focus retention strategies on high-value and frequent customers.
2. Develop targeted campaigns for promising customer segments.
3. Analyze discount effectiveness before expanding promotional campaigns.
4. Strengthen subscription programs to improve customer retention.
5. Align inventory and marketing strategies with seasonal demand.
6. Use customer segmentation to personalize offers and recommendations.


## 📁 Repository Structure

```text
CCustomer_Behavior_Analysis/
│
├── screenshots/
│   ├── dashboard_overview.png
│   └── dashboard_filtered_analysis.png
│
├── Consumer_Behavior_Analysis.sql
├── Consumer_Behavior_Dashboard.pbix
├── Consumer_Shopping_Behavior_Analysis.ipynb
├── customer_shopping_behavior.csv
├── Customer Shopping Behavior Analysis.pdf
├── Customer-Shopping-Behavior-Analysis.pptx
└── README.md
```


## ▶️ How to Run

### Python Analysis

Clone the repository:

```bash
git clone https://github.com/Kruti115/Customer_Behavior_Analysis.git
```

Install required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

Open the Jupyter Notebook:

```text
Consumer_Shopping_Behavior_Analysis.ipynb
```

Run the notebook cells sequentially.

### SQL Analysis

1. Install PostgreSQL.
2. Create a PostgreSQL database.
3. Import the cleaned dataset.
4. Open `Consumer_Behavior_Analysis.sql`.
5. Execute the queries.

### Power BI

Open:

```text
Consumer_Behavior_Dashboard.pbix
```

using Power BI Desktop.


## 📊 Project Deliverables

* Python EDA notebook
* PostgreSQL SQL analysis
* Interactive Power BI dashboard
* Analytical report
* Project presentation


## 🎯 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Python
* Pandas
* SQL
* PostgreSQL
* Power BI
* DAX
* Data Visualization
* Customer Segmentation
* Business Analysis
* Data Storytelling


## 👩‍💻 Author

**Kruti Gupta**

GitHub: https://github.com/Kruti115

LinkedIn: https://www.linkedin.com/in/kruti-gupta-data/
