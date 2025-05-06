# 🍕 Pizza Shop Sales Analysis (SQL Project)

This project focuses on analyzing pizza sales data using SQL and MySQL Workbench. I designed the database schema, built an ER diagram, and solved real-world business questions to derive meaningful insights from raw data.

---

## 🧱 Database Structure

The database (`pizzashop`) contains 4 tables:

- `pizza_types(pizza_type_id, name, category, ingredients)`
- `pizzas(pizza_id, pizza_type_id, size, price)`
- `orders(order_id, order_date, order_time)`
- `order_details(order_details_id, order_id, pizza_id, quantity)`

🖼️ **ER Diagram:**  
![ER_diagram](https://github.com/user-attachments/assets/6d016e19-d884-4204-a225-f9ceb6b30669)

---

## 🚀 Getting Started

1. Clone this repository  
2. Import the SQL data file into MySQL Workbench  
3. Open and run the `solved_queries_with_questions.sql` script to explore the insights  

---

## 📘 Key Learnings

- Writing complex SQL joins, aggregations, and subqueries  
- Designing a normalized relational database  
- Deriving actionable insights from raw data  
- Creating and interpreting ER diagrams  

---

## 📊 Business Questions & SQL Analysis

### 1️⃣ Total Revenue from Pizza Sales

**💡 Explanation:**  
To calculate total revenue, we multiply each pizza's price by its ordered quantity and sum the results.

![image](https://github.com/user-attachments/assets/4adc329d-8d93-4fcc-b83e-08ae757f31b3)

---

### 2️⃣ Top 5 Most Ordered Pizza Types and Their Quantities

**💡 Explanation:**  
We join `pizza_types` and `order_details` to count the total quantity ordered per pizza.

![image](https://github.com/user-attachments/assets/89a4039d-f135-4824-bf57-90ac47d7c9f2)

---

### 3️⃣ Average Number of Pizzas Ordered Per Day

**💡 Explanation:**  
Calculates the average number of pizzas ordered per day by first summing quantities per date and then averaging those daily totals.

![image](https://github.com/user-attachments/assets/c9dd13b1-aec0-471f-bf21-f0822a0b235d)

---

### 4️⃣ Top 3 Least Revenue-Generating Pizza Types

**💡 Explanation:**  
Retrieves the top 3 least revenue-generating pizza types by calculating total revenue (quantity × price) and sorting in ascending order.

![image](https://github.com/user-attachments/assets/bd1822cf-08ab-4381-956d-4826e828bc3f)

---

### 5️⃣ Revenue Contribution of Each Pizza Category (%)

**💡 Explanation:**  
Calculates the percentage contribution of each pizza category to total revenue, sorted from highest to lowest.

![image](https://github.com/user-attachments/assets/7bc08371-ea8b-47e2-8dd2-d4e446cb73aa)

---

## ✅ Summary

This project demonstrates how SQL can be used to uncover valuable business insights from transactional data. By analyzing real-world pizza order data, I was able to:

- Identify top-selling and low-performing pizza types.
- Calculate average daily sales trends.
- Measure revenue contributions by pizza category.
- Create clean, optimized queries using JOINs, aggregation, subqueries, and sorting.

This type of analysis helps businesses improve decision-making for marketing, inventory, and product strategy. It’s a hands-on example of how data analysis and SQL skills can turn raw data into actionable insights.

