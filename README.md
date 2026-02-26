# 🛒 Product Management REST API

## 📌 Project Title
Product Management REST API using Node.js and Express.js

---

## 🎯 Objective
This project is a simple RESTful API built using Node.js and Express.js to manage product data.

It allows users to:
- Get all products
- Get product by ID
- Get products by category
- Add a new product
- Replace a product completely
- Update product stock
- Update product price

---

## 🚀 Implemented Routes

### 1. Server Status
GET /

### 2. Get All Products
GET /products

### 3. Get Product By ID
GET /products/:id  
Example:  
GET /products/1

### 4. Get Product By Category
GET /products/category/:categoryName  
Example:  
GET /products/category/Electronics

### 5. Create New Product
POST /products  

Sample Body (JSON):
{
  "name": "Headphones",
  "category": "Electronics",
  "price": 1999,
  "stock": 15,
  "rating": 4.6
}

### 6. Replace Entire Product
PUT /products/:id

### 7. Update Product Stock
PUT /products/:id/stock  

Sample Body:
{
  "stock": 100
}

### 8. Update Product Price
PUT /products/:id/price  

Sample Body:
{
  "price": 2999
}

---

## 🌐 Sample Local URLs

http://localhost:3000/  
http://localhost:3000/products  
http://localhost:3000/products/1  
http://localhost:3000/products/category/Electronics  

---

## ⚙️ Steps to Run Locally

1. Clone the repository
   git clone <your-repo-link>

2. Go to project folder
   cd project-folder-name

3. Install dependencies
   npm install

4. Start the server
   node index.js

Server will run on:
http://localhost:3000

---

## 🛠 Tech Stack
- Node.js
- Express.js
- JavaScript
- REST API

---

## 📌 HTTP Status Codes Used
- 200 → Success
- 201 → Created
- 400 → Bad Request
- 404 → Not Found

---

## 🔗 Deployed Link
(Add your deployed link here)

##Postman Documentation Link
https://documenter.getpostman.com/view/50840965/2sBXcGDeft
---

## 👨‍💻 Auth
