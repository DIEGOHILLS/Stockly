# Stockly - Inventory Management System

A full-stack inventory management platform built with the PERN stack (PostgreSQL, Express, React, Node.js), featuring multi-user product and stock management, CRUD operations, rate limiting, and production deployment.

Live Demo: https://stockly-aqif.onrender.com/

---

Tech Stack

Frontend: React, TailwindCSS, Daisy UI
Backend: Node.js, Express.js
Database: PostgreSQL
State Management: Zustand
Security: Rate Limiting, Bot Protection

---

Key Features

- Full CRUD Operations - Create, read, update, and delete products with a responsive, intuitive UI built with TailwindCSS and Daisy UI.
- Multi-User Stock Management - Structured data workflows supporting multiple users managing product inventory simultaneously.
- RESTful API Design - Clean, predictable API endpoints with Express.js and PostgreSQL for reliable data handling and retrieval.
- Rate Limiting & Bot Protection - Backend security middleware to prevent abuse and improve application resilience.
- Global State Management - Efficient client-side state handling with Zustand for responsive UI performance and consistent data flow.
- Error Handling - Centralized error middleware on the server and client-side error boundaries for robust debugging and user feedback.
- Light/Dark Theme Toggle - User preference persistence for enhanced UX.

---

Architecture Overview

Client (React + Zustand)
  -> HTTP requests
Server (Node.js + Express)
  -> PostgreSQL queries
Database (PostgreSQL)

---

---

What I Learned

Building Stockly deepened my understanding of relational database design with PostgreSQL and the importance of structured REST API patterns for scalable data operations. I also gained practical experience with backend security practices - implementing rate limiting and bot protection taught me that security isn't an afterthought, it's a feature.

---

API Endpoints

GET /api/products - Fetch all products
GET /api/products/:id - Fetch single product
POST /api/products - Create new product
PUT /api/products/:id - Update product
DELETE /api/products/:id - Delete product

---

Getting Started

Prerequisites:
- Node.js v18+
- PostgreSQL instance (local or cloud)


Installation:
git clone (https://github.com/DIEGOHILLS/Stockly.git)
cd server
npm install
cd ../client
npm install
npm run build
npm start

---
