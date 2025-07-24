# ✈️ Airline Ticketing SQL Case Study

A complete SQL case study designed to analyze an airline's ticketing and flight operations using structured relational data. This project focuses on answering business-relevant questions using SQL queries involving JOINs, aggregations, window functions, CTEs, and time-based calculations.

---

## 🧠 Problem Statement

This project simulates the data infrastructure of an airline ticketing system, with tables including:
- `Airports`: Airport details
- `Airlines`: Airlines operating flights
- `Flights`: Flight schedules with origin/destination
- `Passengers`: Customer data with frequent flyer status
- `Tickets`: Ticket purchases and prices

Using these tables, I wrote queries to uncover operational and customer insights.

---

## 📊 Key Questions Answered

1. **Which airport has the highest number of departures?**  
2. **How many tickets have been sold per airline?**  
3. **List all flights operated by IndiGo with airport names.**  
4. **Top airline by number of departures from each airport.**  
5. **Flight durations and categorization: Short / Medium / Long**  
6. **Each passenger's first and last flight with total number of flights.**  
7. **Highest ticket price sold for each route (origin + destination).**  
8. **Highest-spending passenger in each frequent flyer group.**

---

## 🛠️ Tools & Concepts Used

- SQL Joins (`INNER JOIN`)
- Aggregations (`COUNT`, `SUM`, `MIN`, `MAX`)
- Common Table Expressions (CTEs)
- Window Functions (`ROW_NUMBER`, `RANK`)
- `DATEDIFF` and time calculations
- `CASE` statements for conditional logic

---

## 📁 Project Structure
Airline-Ticketing-SQL-Case-Study/
│
- 📄 DDL and DML.txt               --> SQL code to create tables and insert sample data
- 📄 Airline Ticketing SQL.sql           --> All 8 business insight SQL queries
- 🖼️ ER DIAGRAM.png                --> ER diagram showing relationships between tables
- 📄 README.md                     --> Project overview and documentation

