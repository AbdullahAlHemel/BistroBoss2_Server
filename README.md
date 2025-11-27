# BistroBoss2 Server

[![License](https://img.shields.io/badge/license-ISC-blue.svg)](https://opensource.org/licenses/ISC)

## Overview
**BistroBoss2 Server** is a RESTful backend API built with **Node.js** and **Express.js** for a Bistro/Restaurant application.  
It provides secure endpoints for user authentication, menu management, reviews, and cart operations using **MongoDB** as the database and **JWT** for authentication.

This server is designed to be deployed on platforms like **Vercel** or any Node.js-compatible hosting service.

---

## Features
- **User Management**
  - Register new users
  - Assign admin roles
  - Get all users (admin only)
  - Delete users (admin only)
- **Menu Management**
  - View all menu items
  - Add new menu items (admin only)
  - Delete menu items (admin only)
- **Reviews**
  - View all reviews
- **Cart**
  - Add items to cart
  - View cart by email
  - Remove items from cart
- **Authentication**
  - JWT-based authentication for secure endpoints
  - Admin verification for sensitive operations

---

## Technologies Used
- Node.js
- Express.js
- MongoDB (Atlas)
- JSON Web Tokens (JWT)
- CORS
- dotenv
- Vercel (deployment)

---

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/AbdullahAlHemel/BistroBoss2_Server.git
cd BistroBoss2_Server
