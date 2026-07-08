# Task 6 - Sales Trend Analysis Using SQL Aggregations

## Objective

The objective of this task is to analyze monthly sales trends by calculating total revenue and order volume using SQL aggregate functions. This task demonstrates the use of grouping, filtering, sorting, and aggregation techniques to summarize sales data.

---

## Tools Used

- MySQL
- MySQL Workbench
- GitHub

---

## Dataset

A sample **orders** table was created in MySQL since no dataset was provided for the task.

### Table Structure

| Column | Description |
|---------|-------------|
| order_id | Unique identifier for each order |
| order_date | Date on which the order was placed |
| amount | Revenue generated from the order |
| product_id | Product identifier |

---

## SQL Concepts Used

- SELECT
- YEAR()
- MONTH()
- SUM()
- COUNT()
- COUNT(DISTINCT)
- AVG()
- GROUP BY
- ORDER BY
- WHERE
- LIMIT

---

## Queries Performed

1. Displayed all records from the orders table.
2. Calculated monthly revenue.
3. Calculated monthly order volume.
4. Generated monthly revenue and order volume together.
5. Retrieved the top 3 months with the highest sales.
6. Calculated revenue for a specific year.
7. Calculated average monthly revenue.
8. Identified the highest revenue month.
9. Calculated overall revenue.
10. Counted the total number of orders.

---

## Key Findings

- Monthly revenue was calculated using the **SUM()** aggregate function.
- Monthly order volume was determined using **COUNT(DISTINCT order_id)**.
- **GROUP BY** was used to summarize data by year and month.
- **ORDER BY** sorted the results chronologically and by revenue.
- **LIMIT** was used to identify the top-performing sales months.

---

## Files Included

- `task6.sql` – SQL queries used in the analysis.
- `README.md` – Project documentation.
- `screenshots/` – Output screenshots of SQL queries.

---

## Learning Outcomes

Through this task, I learned how to:

- Analyze sales trends using SQL.
- Perform data aggregation with SQL aggregate functions.
- Group records by month and year.
- Calculate revenue and order volume.
- Sort and filter aggregated results.
- Identify top-performing sales periods using SQL.

---

## Conclusion

This task helped me understand how SQL aggregation functions are used in real-world business scenarios to analyze sales performance. By grouping data by month and year, I was able to calculate revenue trends, measure order volume, and identify the best-performing months. These techniques are essential for business reporting and data analysis.
