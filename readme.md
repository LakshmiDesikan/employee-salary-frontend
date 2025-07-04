# 🌐 Employee Salary Tracker App – Frontend

This is the frontend of the **Employee Salary Tracker Web Application**, designed for both Admin and User roles. It allows users to check their salary credit status and provides admins with control to manage users, update salary status, and reset the system.

## 🔗 Live Demo
➡️ [Netlify Live Site](https://gorgeous-baklava-f5fbcd.netlify.app/) 

## 📦 Tech Stack
- HTML
- CSS
- JavaScript
- Hosted on: **Netlify**

## 🎯 Features
- 🔐 Admin & User Login
- 📅 View Salary Status
- ✍️ Set Salary Credited/Not Credited
- 🌙 Dark Mode Toggle
- 🔄 Reset All User Data (admin only)
- 🔑 Change Password (admin & user)
- 📤 Logout functionality
- 📧 Email notification on user creation

## 🧪 Pages
- `index.html` → Login Page
- `admin.html` → Admin Dashboard
- `user.html` → User Dashboard

## 🌐 How It Works
- Communicates with backend hosted on Render
- Uses `sessionStorage` to manage logged-in sessions
- Frontend calls REST APIs using `fetch()`

## ⚙️ Deployment (Netlify)
1. Push your frontend code to GitHub
2. Connect GitHub repo to Netlify
3. Set build command as `N/A` and publish directory as `/` (if static site)
4. Deploy and get live URL

---
