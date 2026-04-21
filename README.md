# Simple Authentication API

A simple RESTful API built using Node.js, Express, and bcrypt that allows basic user authentication operations. This project is designed as a learning exercise to understand how backend systems handle user registration, login, and password security.

## 🚀 Features
- User registration (POST /register)
- User login (POST /login)
- Password hashing using bcrypt
- Password verification during login
- Basic error handling for invalid credentials or missing users
- JSON request and response handling

## 🧠 What I Learned
- How to build an authentication API using Express
- Understanding user registration and login flow
- How password hashing works using bcrypt
- Comparing hashed passwords securely
- Handling HTTP requests and responses
- Working with in-memory data storage

## ⚙️ Tech Stack
- Node.js
- Express.js
- bcrypt
- JavaScript (ES Modules)

## 📌 Notes
This project uses an in-memory array to store users, so all data will be lost when the server restarts. It is intended for learning purposes only and does not include database integration or advanced authentication methods like JWT.
