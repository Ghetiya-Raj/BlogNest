# 📝 BlogNest – Role-Based MERN Blogging Platform

BlogNest is a full-stack blogging web application built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.

The platform supports **role-based authentication** with two user types:

- 👤 **Reader**
- ✍️ **Author**

Authors can create and manage blogs, while readers can explore and interact with published content.

---

## 🚀 Features

### 🔐 Authentication System

- User registration with:
  - Name
  - Email
  - Password
  - Profile Photo Upload
- Secure login using JWT
- Role selection: **Reader** or **Author**

---

### ✍️ Author Features

- Create new blog posts
- Edit existing blog posts
- Delete blog posts
- Upload blog cover image
- Choose blog visibility:
  - ✅ Public (visible to everyone)
  - ❌ Private (not visible publicly)
- Personal **Dashboard** to manage blogs

---

### 👤 Reader Features

- Browse all public blogs
- Read blog details
- View all registered authors
- Comment on blog posts

---

### 💬 Comment System

- All logged-in users can comment
- Comments displayed under each blog

---

## 🛠️ Tech Stack

### Frontend

- React.js  
- React Router DOM  
- Axios  
- Tailwind CSS / CSS  
- Context API / State Management  

### Backend

- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- JWT Authentication  
- Multer (for image upload)  

---
