# 🤝 Volunteer Management & Donation Tracking System

[![React](https://img.shields.io/badge/Frontend-React.js-61DAFB?style=flat-square&logo=react)](https://reactjs.org/)
[![Node.js](https://img.shields.io/badge/Backend-Node.js-339933?style=flat-square&logo=nodedotjs)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248?style=flat-square&logo=mongodb)](https://www.mongodb.com/)
[![Tailwind CSS](https://img.shields.io/badge/Styling-Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css)](https://tailwindcss.com/)

An enterprise-grade MERN stack application designed to centralize community service logistics, volunteer coordination, and financial transparency.

## 📌 Project Vision
Managing large-scale volunteer operations often suffers from fragmented data and manual tracking. This system resolves those challenges by providing a **unified dashboard** that bridges the gap between organizational needs and volunteer contributions.

---

## ⚡ Key Frontend Features (Core Competencies)
* **Performance-First UI:** Built with **React.js** and **Tailwind CSS**, focusing on high responsiveness and minimal "Layout Shift" (Core Web Vitals).
* **State Management:** Implemented **React Hooks (useContext, useReducer)** for predictable data flow across the volunteer and admin modules.
* **Dynamic Data Fetching:** Integrated **RESTful APIs** with robust error handling and loading states to ensure a seamless UX during high-traffic periods.
* **Role-Based Access Control (RBAC):** Custom-built frontend routing logic to secure administrative views from standard volunteer access.

## 🛠️ Technical Architecture
* **Frontend:** React (Functional Components), JavaScript (ES6+), Tailwind CSS.
* **Backend:** Node.js, Express.js.
* **Security:** JWT-based authentication and Bcrypt password hashing.
* **DevOps:** Version control via Git/GitHub.

---

## 🚀 Getting Started

### Prerequisites
* Node.js (v16.x or higher)
* MongoDB Atlas Account

### Installation
1. **Clone the repository**
   ```bash
   git clone "https://github.com/ShreyashMishra10/Volunteer-Manage-System.git"
   ```
2. **Install Frontend & Backend Dependencies**
   ```Bash
    npm install
   ```
3. **Environment Setup**
Create a .env file in the root:

   ```Code snippet
    PORT=5000
   MONGO_URI=your_connection_string
   JWT_SECRET=your_secure_secret
   ```
4. **Run Development Server**

  ```Bash
    npm run dev
  ```
---
### 📅 Roadmap & Active Development

*  Optimization: Transitioning to Next.js for improved SSR and SEO capabilities.

*  Features: Adding a real-time notification system using Socket.io.

*  Testing: Implementing Unit Testing for core components using Jest.

---

### 👤 Author
Shreyash Mishra 
* GitHub: @ShreyashMishra10
* Role: Software Architect / Full-Stack Developer
