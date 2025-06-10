# 📚 PLP Bookstore – MongoDB Fundamentals Assignment

## Overview
This project demonstrates MongoDB fundamentals, including database setup, CRUD operations, advanced queries, aggregation pipelines, and indexing, using a sample bookstore dataset.

---

## 🚀 Setup Instructions

### 1. Prerequisites
- [Node.js](https://nodejs.org/) installed
- [MongoDB Community Edition](https://www.mongodb.com/try/download/community) running locally **OR** a [MongoDB Atlas](https://www.mongodb.com/atlas/database) cluster
- `npm` (comes with Node.js)

### 2. Install Dependencies
Open a terminal in the project folder and run:

npm install mongodb

### 3. Populate the Database
Run the provided script to insert sample book data:

node insert_books.js

- This will connect to your MongoDB server and populate the `plp_bookstore` database with a `books` collection.

### 4. Run MongoDB Queries
You can run the queries in `queries.js` using the MongoDB Shell (`mongosh`):

1. Start the shell:
    ```
    mongosh
    ```
2. Switch to the database:
    ```
    use plp_bookstore
    ```
3. Copy and paste queries from `queries.js` into the shell to execute them.

---

## 📂 Project Files

- `insert_books.js` – Script to insert sample book data into MongoDB
- `queries.js` – All required MongoDB queries for the assignment
- `Week1-Assignment.md` – Assignment instructions and requirements
- `README.md` – (this file) Setup and usage instructions

---

## 🖼️ Viewing Data

- **MongoDB Compass:**  
  Open Compass, connect to your server, and browse the `plp_bookstore` database and `books` collection to view your data visually.

---

## 📸 Submission

- Ensure you have:
  - `insert_books.js`
  - `queries.js`
  - `README.md` (this file)
  - A screenshot of your MongoDB Compass or Atlas showing your collections and sample data
- Commit and push all files to your GitHub repository.

---

## ℹ️ Notes

- Do **not** add `node_modules/` or sensitive files (like `.env`) to your repository.
- Keep `package.json` and `package-lock.json` in your repo for reproducibility.
- For any issues, refer to the comments in `queries.js` or the assignment document.

---

