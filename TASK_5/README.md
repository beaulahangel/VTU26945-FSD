# 💳 Transaction-Based Payment Simulation

## 📌 Description
This project simulates an online payment system using database transactions.

## ⚙️ Tech Stack
- Node.js
- Express.js
- MySQL

## 🔄 Features
- Deduct balance from user
- Add balance to merchant
- Uses COMMIT on success
- Uses ROLLBACK on failure

## 🏗️ Setup Instructions

### 1. Install dependencies
npm install

### 2. Setup database
Import `db.sql` into MySQL

### 3. Run server
npm start

Server runs at:
http://localhost:3000

## 🧪 API Endpoints

### GET /accounts
View all accounts

### POST /pay
Send money

#### Request Body:
{
  "sender": 1,
  "receiver": 2,
  "amount": 200
}

## ✅ Example Output
Success:
{ "success": true, "message": "Payment successful" }

Failure:
{ "success": false, "message": "Insufficient balance" }

## 📚 Concepts Used
- Database Transactions
- ACID Properties
- Commit & Rollback

## 👨‍💻 Author
Your Name
