# 🚀 MERN Stack Application with Firebase Authentication & Role-Based Access

![MERN Stack](https://img.shields.io/badge/Stack-MERN-brightgreen)
![Firebase](https://img.shields.io/badge/Auth-Firebase-orange)
![TailwindCSS](https://img.shields.io/badge/Style-TailwindCSS-blue)

🔗 **Live Demo:** [https://assignment-frontend-flame.vercel.app/](https://assignment-frontend-flame.vercel.app/)

📌 **Test Credentials:**
- Email: `test@gmail.com`
- Password: `test@01`

A full-stack application built with the MERN stack (MongoDB, Express, React, Node.js) featuring Firebase Authentication and role-based access control. Instructors can create MCQs and Students can attempt them through their respective dashboards.

## ✨ Features

- 🔐 Firebase Authentication (Email/Password)
- 👨‍🏫 Role-based access (Instructor & Student)
- ➡️ Role-based dashboard redirection
- 📝 Instructor Dashboard: Create MCQs
- 📚 Student Dashboard: View & Attempt MCQs
- 🎨 Styled with Tailwind CSS
- 🗄️ MongoDB for data persistence

## 📋 Assignment Requirements

### 1. Firebase Authentication
- Implemented Firebase Authentication for user login
- User role stored in both Firebase (Custom Claims) and MongoDB

### 2. Role-Based Redirect
- Instructor → `/instructor-dashboard`
- Student → `/student-dashboard`

### 3. Instructor Dashboard
- Form to create Multiple Choice Questions (MCQs) with:
  - Question text
  - Multiple options
  - Correct answer
- Questions saved to MongoDB

### 4. Student Dashboard
- Displays MCQs created by instructors
- Allows students to attempt questions

### 5. Frontend
- Built with React
- Styled with Tailwind CSS

### 6. Backend
- Node.js with Express
- APIs for:
  - Login/Authentication
  - Role management
  - MCQ operations

### 7. Database (MongoDB)
- Collections:
  - `Users`: email, role, firebase_uid
  - `Questions`: question_text, options, correct_answer

## 🛠️ Tech Stack

| Category       | Technologies                          |
|----------------|---------------------------------------|
| Frontend       | React, Tailwind CSS                   |
| Backend        | Node.js, Express                      |
| Authentication | Firebase                              |
| Database       | MongoDB                               |

## 🚀 Getting Started

### Prerequisites
- Node.js (v14+)
- MongoDB Atlas account or local MongoDB
- Firebase project with Email/Password auth enabled

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/mern-firebase-auth-app.git
cd mern-firebase-auth-app
