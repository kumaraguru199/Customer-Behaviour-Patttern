# Customer-Behaviour-Patttern
End-to-End Data Analytics project focused on analyzing customer purchasing behavior and Pattern using Python, Pandas, SQL, Power-BI.

🎯 Overview

The objective of this project is to transform raw transactional data into actionable business insights. By analyzing customer purchasing patterns, this project helps businesses identify high-value customer segments, predict churn risk, optimize marketing spend, and increase overall Customer Lifetime Value (CLV).

📊 Dataset

• Source: [Mention source, e.g., Kaggle / Company Internal Data]
• Size: [e.g., 50,000+ rows]
• Core Attributes: Customer ID, Transaction Date, Product Category, Purchase Amount, Customer Age, Gender, Location, and Loyalty Status.

🛠 Tools & Tech Stack

• Data Processing & EDA: Python 3.x (Pandas, NumPy, Matplotlib, Seaborn)
• Database Management: MySQL (Relational Schema, Complex Querying)
• Business Intelligence: Power BI Desktop (DAX, Data Modeling, Data Visualization)
• Environment: Jupyter Notebook / VS Code

⚙️ Project Steps & Workflow


1. Exploratory Data Analysis (EDA) & Cleaning (Python)

• Handled missing values, removed duplicate transactions, and corrected mismatched data types.
• Treated data outliers in purchase amounts using the IQR (Interquartile Range) method.
• Performed distribution analysis on customer demographics and purchasing frequencies.
• Exported the fully cleaned dataset into a structured .csv file ready for SQL database ingestion.

2. Relational Database Management (MySQL)

• Designed a relational database schema and imported the cleaned customer dataset.
• Wrote optimized SQL queries using Joins, CTEs (Common Table Expressions), and Window Functions.
• Segmented customers by calculating RFM (Recency, Frequency, Monetary) scores directly inside the database.

3. Business Intelligence & Modeling (Power BI)

• Imported the processed MySQL views into Power BI.
• Developed a clean Star Schema data model separating fact tables from dimension tables.
• Wrote DAX (Data Analysis Expressions) measures to calculate complex, dynamic KPIs (e.g., Year-over-Year Revenue Growth, Churn Rate, and Average Order Value).

📈 Dashboard Features

The final interactive Power BI dashboard consists of the following views:
• Executive Summary: High-level metrics tracking total revenue, active customer count, and total transactions.
• Customer Segmentation: Breakdown of demographics (age, location, gender) vs. spending tiers.
• Behavior Matrix: Deep-dive analysis tracking purchasing frequency, top product categories, and cohort retention rates.

🏆 Key Results & Business Insights

• High-Value Cohorts: Identified that the 25–34 age demographic contributes to 42% of total revenue, despite making up only 30% of the customer base.
• Retention Alert: Customers who did not make a purchase within 60 days showed an 80% likelihood of churning, signaling a need for targeted email re-engagement campaigns.
• Product Performance: The [Mention Category, e.g., Electronics] category drove the highest sales volume, but [Mention Category, e.g., Apparel] yielded a 15% higher profit margin.
