# 🎬 BingePlay: OTT Streaming Analytics 

## 📌 Project Overview
BingePlay is a fictional Indian OTT streaming service. As part of the analytics team, I was tasked with analyzing a database of 3,000+ users, 100,000+ watch sessions, and 4,400+ subscriptions to answer critical business questions. This project transitions from fundamental revenue reporting to advanced churn detection and cohort analysis.

## 🛠️ Tech Stack
* **Database:** MySQL
* **Language:** Python, SQL
* **Libraries:** pandas, SQLAlchemy, pymysql
* **Environment:** Jupyter Notebook (VS Code)

## 📊 Key Business Questions Answered
1. **Revenue & Growth:** Calculated active Monthly Recurring Revenue (MRR) and tracked H1 2024 signup momentum.
2. **Content Strategy:** Compared user satisfaction between BingePlay Originals vs. Acquired content.
3. **User Behavior:** Identified "super-bingers" and tracked cliffhanger comeback rates.
4. **Product Intelligence:** 
   * Resolved the "Gaps-and-Islands" problem to find users with 4+ consecutive weeks of engagement.
   * Built a churn-signal detection query to identify users whose watch time dropped by >50% month-over-month.

## 🧠 Advanced SQL Concepts Demonstrated
* **Window Functions:** `ROW_NUMBER()`, `LAG()`, `LEAD()`
* **CTEs (Common Table Expressions):** Used extensively for breaking down complex, multi-step calculations (e.g., separating window functions from `WHERE` clauses).
* **Data Quality Handling:** Safely managing `NULL` traps using `LEFT JOIN` and `NOT EXISTS` anti-joins.
* **Date/Time Manipulation:** `DATEDIFF()`, `DATE_ADD()`, and ISO week calculations.

## 🚀 How to Run
1. Execute the provided `.sql` setup script in your local MySQL instance.
2. Update the SQLAlchemy connection string in the Jupyter Notebook with your local database credentials.
3. Run all cells to view the pandas DataFrames outputs.
