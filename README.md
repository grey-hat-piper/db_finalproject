# db_finalproject
E-commerce database design PLP final_project(Question 1)
# 🛒 Easy-buy E-commerce Database

## 📌 Project Overview
Easy-buy is a **relational database system** built using **MySQL** for a campus-focused e-commerce store.  
It is designed to allow **students in a university** to buy and sell items easily, while maintaining a **well-structured, normalised, and efficient database**.  

The database supports:  
- Managing **customers (students)** and their addresses  
- Managing **products** with categories and stock  
- Tracking **orders, payments, and carts**  
- Enforcing **constraints** (PRIMARY KEY, FOREIGN KEY, UNIQUE, NOT NULL)  
- Supporting different **relationships** (One-to-One, One-to-Many, Many-to-Many)  

The schema is fully normalised up to **3rd Normal Form (3NF)**.

---

## 📂 Database Schema
Main tables in this project:
- `Customers`
- `Addresses`
- `Categories`
- `Products`
- `Orders`
- `OrderDetails`
- `Payments`
- `Cart`

ER Diagram:
![ER Diagram](Easybuy.drawio)

---

## 🚀 Getting Started

### ✅ Prerequisites
Before running the project, ensure you have:
- [MySQL Workbench](https://dev.mysql.com/downloads/workbench/) or any SQL client
- Git (for cloning the repo)

---

### ⚡ Installation & Setup

1. **Clone the repository**
[CMD]
- git clone https://github.com/<your-username>/db_finalproject
- cd db_finalproject

2. **restore the easybuy database from the backup file**
[CMD]
- mysql -u <user> -p <database_name> < easybuy.sql
- input user password
- launch mysql to view database

