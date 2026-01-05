# Customer_Behavior_Analysis
Data Analytics Project : Customer Behavior Analysis using SQL, Power BI and Python

📌 Overview

This project performs an end-to-end data analytics workflow on a customer shopping behavior dataset to uncover purchasing patterns, customer preferences, and business insights.

The analysis covers:

Data cleaning and exploratory data analysis (EDA) using Python

Analytical querying using PostgreSQL

Interactive dashboard development in Power BI

Insight reporting and presentation using Gamma

The project demonstrates practical skills required for Data Analyst roles, including data handling, SQL analytics, visualization, and stakeholder communication.

📂 Dataset

File: customer_shopping_behavior.csv

Description:
The dataset contains customer demographic details, purchasing behavior, product attributes, and transaction-related information.

Size:
Rows: 3,900
Columns: 18

📊 Key Columns
Customer ID – Unique customer identifier
Age, Gender, Location – Customer demographics
Item Purchased, Category, Size, Color, Season – Product details
Purchase Amount (USD) – Transaction value
Review Rating – Customer feedback score
Subscription Status – Subscription membership indicator
Shipping Type – Delivery method used
Discount Applied, Promo Code Used – Promotion details
Previous Purchases – Customer purchase history
Payment Method – Mode of payment
Frequency of Purchases – Buying frequency

🛠 Tools & Technologies

Python – Data loading, cleaning, EDA, Pandas, NumPy, Matplotlib, Seaborn
PostgreSQL – SQL-based data analysis
Power BI – Interactive dashboards and KPIs
Gamma – Presentation (PPT) creation
Jupyter Notebook – Analysis and documentation
Git & GitHub – Version control and project hosting

🔍 Project Workflow
1. Data Loading
Imported CSV dataset using Pandas.
Verified schema, data types, and data consistency.

2. Data Cleaning
Checked and handled missing values.
Removed duplicate records.
Standardized categorical values.
Converted columns to appropriate data types.

3. Exploratory Data Analysis (EDA)
Customer demographics analysis (age, gender, location).
Purchase amount distribution and spending patterns.
Category-wise and season-wise sales analysis.
Impact of discounts, promo codes, and subscriptions.
Visualization of trends and correlations.

4. SQL Analysis (PostgreSQL)
Loaded cleaned data into PostgreSQL.
Performed analytical queries such as:
Total and average purchase amount by category
Customer segmentation by purchase frequency
Subscription vs non-subscription behavior
Discount and promo code impact analysis

5. Power BI Dashboard
Designed an interactive dashboard featuring:
Total revenue and average order value
Top-selling categories and items
Customer segmentation insights
Filters by season, location, and gender

6. Reporting & Presentation
Documented insights in a structured report.
Created a professional presentation using Gamma to summarize findings and recommendations.

📊 Dashboard Highlights

Revenue and purchase trends
Category-wise and season-wise performance
Subscription and discount impact analysis
Interactive slicers for customer demographics

📈 Key Insights & Results

Identified high-performing product categories and seasons.
Analyzed how discounts and promo codes influence spending.
Compared purchasing behavior of subscribed vs non-subscribed customers.
Highlighted customer segments with high purchase frequency and value.

▶️ How to Run This Project
1. Clone the Repository
git clone https://github.com/Kruti115/Customer_Behavior_Analysis.git

3. Install Dependencies
pip install pandas numpy matplotlib seaborn

4. Run Python Analysis
Open the Jupyter Notebook.
Execute cells sequentially for cleaning and EDA.

5. PostgreSQL Setup
Create a PostgreSQL database.
Import the cleaned dataset.
Run SQL queries from the /sql folder.

6. Power BI Dashboard
Open the .pbix file in Power BI Desktop.

Refresh data connections if required.

🎯 Project Outcome

This project showcases:
- Strong data cleaning and EDA skills
- Practical SQL analytics using PostgreSQL
- Business-focused Power BI dashboarding
- Clear insight communication through reports and presentations
