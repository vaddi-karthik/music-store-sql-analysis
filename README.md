# 🎵 Music Store Customer & Sales Analysis | SQL

Analyzed a relational Music Store database containing 11 interconnected tables using SQL to uncover customer behavior, sales trends, genre popularity, and revenue insights through business-driven analysis.

---

## 📌 Project Overview

This project analyzes a relational Music Store database containing 11 interconnected tables. Using SQL, the project answers real-world business questions related to customer spending, genre popularity, artist performance, and regional sales trends — transforming raw data into actionable business insights.

---

## 🚀 Business Questions Answered

1. Who is the senior most employee based on job title?
2. Which countries have the most invoices?
3. What are the top 3 values of total invoice?
4. Which city has the best customers? *(for a promotional Music Festival)*
5. Who is the best customer by total spending?
6. Which customers listen to Rock Music?
7. Who are the top 10 Rock artists by track count?
8. Which tracks have a song length longer than average?
9. How much has each customer spent per artist?
10. What is the most popular music genre for each country?
11. Who is the top spending customer for each country?

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Database | MySQL / PostgreSQL |
| Query Language | SQL |
| Concepts Used | JOINs, CTEs, Subqueries, Window Functions, Aggregate Functions, GROUP BY, RANK() |
| Design Tool | MySQL Workbench (ER Diagram) |

---

## 🗂️ Database Schema

The Music Store database contains 11 tables:

| Table | Description |
|---|---|
| `employee` | Employee details and reporting hierarchy |
| `customer` | Customer info and assigned support representatives |
| `invoice` | Transaction details — billing address, date, total |
| `invoice_line` | Individual purchase items per invoice |
| `track` | Song details — duration, price, genre, album |
| `album` | Collections of tracks by artists |
| `artist` | Music artist details |
| `genre` | Music category classification |
| `media_type` | Track format definitions |
| `playlist` | Playlist management |
| `playlist_track` | Tracks associated with playlists |

---

## 📷 Schema Diagram

![Schema Diagram](schema_diagram.png)

*Entity Relationship diagram showing relationships across 11 interconnected tables.*

---

## 📁 Project Structure

```
music-store-sql-analysis/
│
├── Music_Store.sql              # All SQL queries
├── Music_Store_ER.mwb           # MySQL Workbench ER model
├── schema_diagram.png           # Visual schema diagram
├── Music_store_Raw_data/        # Raw CSV dataset files
│   ├── album.csv
│   ├── artist.csv
│   ├── customer.csv
│   ├── employee.csv
│   ├── genre.csv
│   ├── invoice.csv
│   ├── invoice_line.csv
│   ├── media_type.csv
│   ├── playlist.csv
│   ├── playlist_track.csv
│   └── track.csv
└── README.md
```

---

## 📊 Project Outcomes

- Solved 11 real-world business problems using SQL analysis
- Queried data across 11 interconnected relational tables
- Identified top revenue-generating cities and high-value customer segments
- Discovered country-wise genre and artist performance trends
- Generated business recommendations for marketing and customer engagement

---

## 💡 Key Business Insights

- **High-revenue cities** should be prioritized for music festivals and promotional campaigns
- **Top customers** contribute disproportionately to revenue — loyalty programs can improve retention
- **Rock genre** dominates purchases — active promotion of rock artists drives engagement
- **Country-wise genre trends** reveal regional preferences that support localized marketing
- **Top spending customers per country** can be targeted with personalized exclusive offers

---

## ⚙️ How to Run

```sql
-- 1. Import the raw CSV files into your MySQL/PostgreSQL database
-- 2. Open Music_Store.sql in your SQL client
-- 3. Run individual queries to explore business insights
```

---

## 🧠 SQL Concepts Used

- `INNER JOIN` / `LEFT JOIN` across multiple tables
- `GROUP BY` with `ORDER BY` for aggregations
- `CTEs` (Common Table Expressions) for readable complex queries
- `Window Functions` — `RANK()`, `ROW_NUMBER()`
- `Subqueries` for nested filtering
- `Aggregate Functions` — `SUM()`, `COUNT()`, `AVG()`
- `CASE` statements for conditional logic

---

## 👨‍💻 Author

**Karthik Vaddi**
B.Tech in Artificial Intelligence & Machine Learning
📧 vaddikarthik2004@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/karthik-vaddi-581193268/)
🐙 [GitHub](https://github.com/vaddi-karthik)
