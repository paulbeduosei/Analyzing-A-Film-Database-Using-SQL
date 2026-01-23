🎬 Analyzing Film Rental Data Using SQL

📌 Project Overview

This project uses SQL to analyze a film rental database and answer real-world business questions using relational data. The goal was to demonstrate how SQL can be used not just 

to retrieve data, but to analyze customer behavior, revenue patterns, and product performance in a structured business setting.

This project simulates work done for a client in the entertainment / media rental industry, where understanding customer demand and revenue drivers is critical for decision-

making.

🧠 Business Questions Answered

The analysis focused on answering questions such as:

Which film languages and categories are rented the most?

Who are the most valuable customers based on total spending?

How does revenue change by month and time of day?

Which film genres tend to have longer runtimes?

Which films are rented most frequently?

These questions help stakeholders understand what content performs best and where revenue opportunities exist.

🔧 Tools & Technologies

SQL

Relational databases

Joins (INNER, LEFT)

Aggregations (COUNT, SUM, AVG)

Date & time functions

Subqueries

String manipulation

Data filtering and sorting

🔍 Analysis Process (Step-by-Step)

1️⃣ Understanding the Data Structure

I first reviewed the database schema to understand how tables were related (films, customers, payments, inventory, categories).

Why: This step is critical for writing accurate joins and avoiding duplicated or misleading results.

2️⃣ Joining Tables

Multiple tables were joined to create a complete view of rentals and payments.

Why: Business insights often live across multiple tables, not in isolation.

3️⃣ Data Cleaning & Filtering

Unnecessary columns were removed, and filters were applied based on language, category, and customer activity.

Why: Cleaner data leads to clearer insights and more accurate metrics.

4️⃣ Aggregation & Metric Creation

I calculated totals, averages, and counts to measure:

Total revenue

Rental frequency

Average film length

Customer lifetime value

Why: Aggregations turn raw data into KPIs decision-makers can understand.

5️⃣ Time-Based Analysis

I extracted month, hour, and day from timestamps to analyze rental and revenue trends over time.

Why: Time patterns help businesses plan promotions and staffing.

6️⃣ Insight Generation

Results were interpreted to highlight:

High-performing genres and films

Revenue-driving customers

Usage trends throughout the day and year

Why: The value of analytics comes from translating numbers into decisions.

📊 Key Insights

Certain film categories consistently drive higher rental volume.

A small group of customers contributes a large portion of total revenue.

Rental activity varies significantly by time of day and month.

Longer films tend to cluster within specific genres.

🎯 Business Impact

This analysis could help a rental business:

Optimize inventory by focusing on high-performing genres

Design targeted promotions for top customer segments

Improve revenue forecasting using time-based trends
