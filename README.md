# 🎵 SQL Project – Music Store Analysis

This project analyzes a music store database using SQL. It answers business questions grouped into three difficulty levels: **Easy**, **Moderate**, and **Advanced**, using real-world data from a fictional music store.

---

## 📌 Project Overview

The project explores:
- Top spending customers
- Genre popularity by country
- Artists and track trends
- City-level sales patterns

---

## 🧠 Questions Solved

### 🟢 Easy
- Who is the senior-most employee?
- Which country has the most invoices?
- Top 3 invoice values
- City with the highest revenue
- Best customer by total spend

### 🟡 Moderate
- Rock music listeners (by email)
- Top 10 rock music artists
- Tracks longer than average length

### 🔴 Advanced
- Amount spent by each customer on the top artist
- Most popular genre per country
- Top customer per country by spending

---

## 📊 SQL Concepts Used

This project demonstrates intermediate to advanced SQL skills, including:

- **JOINs** (INNER, LEFT): to combine data from customers, invoices, tracks, artists, etc.
- **Aggregate Functions**: `SUM()`, `COUNT()`, `AVG()` to derive insights
- **GROUP BY + ORDER BY**: to segment and sort data
- **Window Functions**: using `ROW_NUMBER()` to rank top performers by country
- **Common Table Expressions (CTEs)**: for readability and breaking down complex logic
- **Subqueries**: used for filtering based on aggregated conditions
- **DISTINCT**: to eliminate duplicates
- **Filtering with WHERE & HAVING**

Each query is documented and organized by difficulty:  
🟢 Easy – Exploratory queries  
🟡 Moderate – Filtering, subqueries, and distinct use  
🔴 Advanced – CTEs, window functions, and business logic

---

## 🛠️ Technologies Used
- PostgreSQL
- pgAdmin
- SQL

---

## 📁 Files Included

- `music_store_analysis.sql`: Full SQL script with all queries
- `README.md`: This file

---

## ▶️ How to Run This Project

1. Open **pgAdmin**
2. Create a database and load the sample Chinook schema (if needed)
3. Go to **Query Tool**
4. Click **File → Open** → Select `music_store_analysis.sql`
5. Click **Run** (⚡ icon)

---

## 🔗 Download SQL File
[Click to view raw SQL file](https://1drv.ms/u/c/9ee0b891366d7cb1/EbwgGbE3T-5IhBHaAcc6FpIB0qhm4UvT78SBpvPysgMwgg?e=Rh5jC8)

---

## 📬 Author
- [Shivani Jain](https://github.com/ShivaniJain1811)
