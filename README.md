# ShopEZ 🛒  
A Full-Stack E-Commerce Web Application (MERN Stack)

## 🔗 Live Demo
👉 https://sbmern.vercel.app/

---

## 📌 Overview
ShopEZ is a full-stack e-commerce web application built using the MERN stack.  
It supports multiple user roles and provides a complete online shopping workflow, from product listing to order management.

This project was developed to strengthen my understanding of full-stack web development, REST APIs, and real-world application architecture.

---

## 👥 User Roles
- **Admin**
  - Manage users and sellers
  - Oversee platform operations

- **Seller**
  - Add, update, and manage products
  - Track inventory and orders

- **Buyer**
  - Browse products
  - Add items to cart and wishlist
  - Place and track orders

---

## ✨ Key Features
- User authentication and role-based access
- Product search and filtering
- Cart and wishlist management
- Order lifecycle management
- Responsive UI for desktop and mobile
- Secure API integration between frontend and backend

---

## 🛠️ Tech Stack

### Frontend
- React.js
- HTML5, CSS3
- JavaScript (ES6+)

### Backend
- Node.js
- Express.js
- RESTful APIs

### Database
- MongoDB

### Tools & Platforms
- Git & GitHub
- Vercel (Frontend Deployment)

---

## ⚙️ Environment Variables
Sensitive data such as API keys and secrets are managed using environment variables and are **not included in the repository**.

Example:
```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```
# Local Setup Guide – ShopEZ 🛠️

This document explains how to run the ShopEZ application locally for development and testing purposes.

---

## 📋 Prerequisites
Ensure the following are installed on your system:
- Node.js (v16 or later)
- npm (Node Package Manager)
- MongoDB (local instance or MongoDB Atlas)

---


---

## 🔽 Clone the Repository
```bash
git clone https://github.com/jiyasangwan/ShopEZee.git
cd ShopEZee

⚙️ Backend Setup
1️⃣ Navigate to the server directory
cd server

2️⃣ Install backend dependencies
npm install

3️⃣ Create .env file

Create a .env file inside the server folder and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret


Note: The .env file is ignored by Git for security reasons.

4️⃣ Start the backend server
npm start


The backend server will run on:

http://localhost:5000

🎨 Frontend Setup
1️⃣ Navigate to the client directory
cd ../client

2️⃣ Install frontend dependencies
npm install

3️⃣ Start the frontend application
npm run dev


The frontend will be available at:

http://localhost:5173

🔗 Connecting Frontend and Backend

Ensure that the API base URL in the frontend is pointing to:

http://localhost:5000

