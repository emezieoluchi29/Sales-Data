# Sales-Data
 SQL Project

## Project Overview

This project involves creating and managing a database for an e-commerce platform. The database includes the following tables: `OrderItem`, `Order`, `Product`, `Supplier`, and `Customer`.

## Table Descriptions

### 1. OrderItem Table
The `OrderItem` table stores information about individual items within an order.
 orderItemID 
 company name
 contact name
 contact title
 city
 country
 phone
 fax

 ### 2. Order Table
The `Order` table stores information about customer orders.
 orderID
 customerID
 orderDate
 ordernumber
 totalAmount

### 3. Product Table
The `Product` table stores information about products available for sale.
 productID 
 product name 
 unity price
 package
 supplierID
 discontinued

### 4. Supplier Table
The `Supplier` table stores information about suppliers who provide the products.
 supplierID
 productID
 orderID
unit price
qunatity
 
### 5. Customer Table
The `Customer` table stores information about customers who place orders.
 customerID  
 First name   
 Last name
 City
 Country
 phone
