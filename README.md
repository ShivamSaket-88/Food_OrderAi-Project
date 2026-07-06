# 🍔 Food Order AI Project

A modern **Food Ordering Web Application** built using the **MERN Stack** with **Groq AI Review Summary**, **Stripe Payment Gateway**, and **Role-Based Authentication**.

> Developed as the final project for the **Web Stack Academy (WSA) Full Stack Web Development Internship**.

---

# 📖 Table of Contents

- Project Overview
- Features
- Tech Stack
- System Architecture
- Project Modules
- AI Review Summary
- Payment Integration
- Installation
- Environment Variables
- Folder Structure
- API Endpoints
- Future Enhancements
- Author

---

# 🚀 Project Overview

Food Order AI Project is a complete MERN Stack Food Ordering application where users can:

- Browse restaurants
- View restaurant menus
- Add food items to cart
- Place online orders
- Make payments using Stripe
- View previous orders
- Manage profile
- Generate AI Review Summary using Groq AI

The project also provides an Admin Panel to manage restaurants and food items.

---

# ✨ Features

## 👤 User

- User Registration
- User Login
- JWT Authentication
- Restaurant Listing
- Restaurant Search
- View Food Menu
- Add to Cart
- Update Cart
- Remove Items
- Stripe Payment
- Order Success Page
- Order History
- User Profile
- AI Review Summary

---

## 👨‍💼 Admin

- Add Restaurant
- Add Food Items
- Upload Images
- Manage Menus
- Role Based Access
- Protected Routes

---

# 🤖 AI Review Summary

This project integrates the **Groq AI API**.

Instead of reading hundreds of customer reviews, users can generate an AI-powered summary.

### Workflow

Customer Reviews

↓

Groq AI API

↓

AI Generated Summary

↓

Displayed to User

Benefits

- Saves Time
- Better User Experience
- Quick Decision Making

---

# 💳 Stripe Payment

Secure payment integration using Stripe Checkout.

Flow

Cart

↓

Checkout

↓

Stripe Payment

↓

Payment Success

↓

Order Created

---

# 🛠 Tech Stack

## Frontend

- React.js
- Redux Toolkit
- React Router
- Axios
- Bootstrap
- React Toastify

---

## Backend

- Node.js
- Express.js
- MongoDB
- Mongoose

---

## Authentication

- JWT Authentication
- Cookies

---

## Cloud

- Cloudinary

---

## AI

- Groq AI API

---

## Payment

- Stripe Payment Gateway

---

# 🏗 System Architecture

```
React Frontend
        │
        │ Axios
        ▼
Express.js API
        │
        ▼
Node.js Server
        │
        ▼
MongoDB Database
```

External Services

- Stripe
- Cloudinary
- Groq AI

---

# 📂 Project Modules

## User Module

- Register
- Login
- Restaurants
- Menu
- Cart
- Checkout
- Orders
- Profile

---

## Restaurant Module

- Restaurant List
- Search
- Details

---

## Menu Module

- View Menu
- Food Details

---

## Cart Module

- Add Item
- Remove Item
- Quantity Update

---

## Payment Module

- Stripe Checkout
- Payment Success

---

## AI Module

- Review Collection
- Groq AI Summary
- Summary Display

---

# 🔒 Authentication

JWT Token Based Authentication

Protected Routes

- Profile
- Orders
- Cart
- Admin Pages

Role Based Access

Admin

- Add Restaurant
- Add Menu

User

- Order Food
- Payment
- Orders

---


# ⚙ Installation

Clone Repository

```bash
git clone https://github.com/ShivamSaket-88/Food_OrderAi-Project.git
```

Backend

```bash
cd backend
npm install
npm run dev
```

Frontend

```bash
cd frontend
npm install
npm run dev
```

---

# 🔑 Environment Variables

Backend

```env
PORT=

MONGODB_URI=

JWT_SECRET=

JWT_EXPIRES=

JWT_EXPIRES_TIME=

STRIPE_SECRET_KEY=

STRIPE_WEBHOOK_SECRET=

CLOUDINARY_CLOUD_NAME=

CLOUDINARY_API_KEY=

CLOUDINARY_API_SECRET=

GROQ_API_KEY=
```

---

# 📁 Folder Structure

```
Food_OrderAi-Project

backend/
controllers/
models/
routes/
middlewares/
utils/

frontend/
src/
components/
redux/
pages/
utils/
```

---

# 📌 API Endpoints

## User

POST

```
/api/v1/users/signup
```

POST

```
/api/v1/users/login
```

GET

```
/api/v1/users/me
```

---

## Restaurants

GET

```
/api/v1/eats/stores
```

---

## Menu

GET

```
/api/v1/eats/menus
```

---

## Cart

POST

```
/api/v1/eats/cart
```

GET

```
/api/v1/eats/cart/get-cart
```

---

## Orders

POST

```
/api/v1/eats/orders
```

GET

```
/api/v1/eats/orders/me
```

---

# 🚀 Future Improvements

- Google Login
- Email Verification
- Push Notifications
- Live Order Tracking
- Wishlist
- Coupon System
- Ratings & Reviews
- Multi-language Support
- Dark Mode
- Mobile App

---

# 👨‍💻 Author

## Shivam Saket

B.Tech (Computer Science and Engineering)

Rewa Engineering College

GitHub

https://github.com/ShivamSaket-88

---

# 🙏 Acknowledgements

Special thanks to

- Web Stack Academy (WSA)
- Richa Ma'am

for their continuous guidance and support throughout the internship.

---

## ⭐ If you like this project, don't forget to Star this repository.
