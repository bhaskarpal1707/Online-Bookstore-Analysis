# 📚 SQL Analysis Project – Online Book Store

 ![Image 1](https://github.com/bhaskarpal1707/Online-Bookstore-Analysis/blob/main/Image%201.jpg)

## 🛠️ **Project Overview**
This project is a detailed **SQL analysis** of an online book store using **PostgreSQL**. The goal was to manage and analyze book, customer, and order data by writing and executing **11 basic queries** and **9 advanced queries**. 

### ✅ **Objective**
- Perform SQL operations to **retrieve, analyze, and manipulate data** efficiently.
- Gain insights into **customer behavior, revenue trends, and stock management**.
- Optimize SQL query performance.

---

## 📊 **Datasets Used**
### 1. **Books Dataset**
- **Columns:** Book ID, Title, Author, Genre, Price, Stock, Published Year  
- **Details:** Contains information about book titles, genres, authors, prices, and stock levels.  

### 2. **Customer Dataset**
- **Columns:** Customer ID, Name, Email, City, Country  
- **Details:** Stores customer details such as name, address, city, and country.  

### 3. **Order Dataset**
- **Columns:** Order ID, Customer ID, Book ID, Quantity, Order Date, Total Amount  
- **Details:** Includes information about customer orders, book quantities, and total order amounts.

   ![Image 2](https://github.com/bhaskarpal1707/Online-Bookstore-Analysis/blob/main/Image%202.jpg) 

---

## 🔎 **Basic Queries**
1. Retrieve all books in the "Fiction" genre  
2. Find books published after the year 1950  
3. List all customers from Canada  
4. Show orders placed in November 2023  
5. Retrieve the total stock of books available  
6. Find the details of the most expensive book  
7. Show all customers who ordered more than 1 quantity of a book  
8. Retrieve all orders where the total amount exceeds $20  
9. List all genres available in the Books table  
10. Find the book with the lowest stock  
11. Calculate the total revenue generated from all orders  

---

## 🚀 **Advanced Queries**
1. Retrieve the total number of books sold for each genre  
2. Find the average price of books in the "Fantasy" genre  
3. List customers who have placed at least 2 orders  
4. Find the most frequently ordered book  
5. Show the top 3 most expensive books of the 'Fantasy' genre  
6. Retrieve the total quantity of books sold by each author  
7. List the cities where customers who spent over $30 are located  
8. Find the customer who spent the most on orders  
9. Calculate the stock remaining after fulfilling all orders  

---

 ![Image 3](https://github.com/bhaskarpal1707/Online-Bookstore-Analysis/blob/main/Image%203.jpg)

## ⚙️ **Challenges and Solutions**
### 1. **Handling NULL Values**
- **Challenge:** Joins involving missing data returned incomplete results.  
- **Solution:** Used `COALESCE()` to replace NULL values with default values, ensuring complete data retrieval.  

### 2. **Query Performance Optimization**
- **Challenge:** Slow performance for large datasets.  
- **Solution:** Applied `INDEX` on frequently queried columns to speed up data retrieval.  

### 3. **Date Range Management**
- **Challenge:** Difficulty in filtering data by specific time periods.  
- **Solution:** Used `BETWEEN` for easy filtering by date range.  

---

## 🔥 **Key Insights and Outcomes**
- **Revenue Insights:** Identified total revenue generated from all orders.  
- **Customer Analysis:** Found high-spending customers and their locations.  
- **Genre Trends:** Analyzed the total books sold by genre.  
- **Stock Management:** Calculated remaining stock after fulfilling all orders.  
- **Frequently Ordered Books:** Identified the most popular books.  

---

## 🔥 **Future Enhancements**
- Add more complex queries with **subqueries and window functions**.  
- Implement **triggers** for automatic stock updates.  
- Introduce **stored procedures** for repetitive operations.  

---

## 🛠️ **Tech Stack**
- PostgreSQL  
- SQL Queries  
- Data Analysis  
- Database Management  
