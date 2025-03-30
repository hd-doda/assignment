📚 MERN Stack Application with Firebase Authentication & Role-Based Redirect
🚀 Overview
This project is a MERN stack application that integrates Firebase Authentication with role-based access control. Users are categorized as Instructors or Students, and upon login, they are redirected to their respective dashboards.

🔥 Features
Firebase Authentication 🔑 (Email/Password login)

Role Management (Instructor & Student) stored in Firebase & MongoDB

Role-Based Redirection 🚦

📖 Instructors can create Multiple Choice Questions (MCQs)

🎓 Students can attempt MCQs

Instructor Dashboard 🎤

Create MCQs with options & correct answer

Save MCQs to MongoDB

Student Dashboard 📝

Fetch & display MCQs

Attempt questions

Backend APIs 🚀 (Node.js & Express)

Authentication & Role Management

Store & fetch MCQs

Frontend UI 🌟 (React + Tailwind CSS)

🛠️ Tech Stack
Frontend: React ⚛️ + Tailwind CSS 🎨

Backend: Node.js 🚀 + Express.js 🖥️

Authentication: Firebase 🔥

Database: MongoDB 🍃

📌 Database Schema
Users Collection
json
Copy
Edit
{
  "email": "user@example.com",
  "role": "instructor",
  "firebase_uid": "unique_firebase_id"
}
Questions Collection
json
Copy
Edit
{
  "question_text": "What is React?",
  "options": ["Library", "Framework", "Language", "None"],
  "correct_answer": "Library"
}
📖 Setup Instructions
1️⃣ Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/repo-name.git
2️⃣ Install dependencies:

bash
Copy
Edit
cd repo-name
npm install
3️⃣ Set up Firebase & MongoDB connection in .env
4️⃣ Run the project:

bash
Copy
Edit
npm start
🎯 How It Works
User logs in using Firebase Authentication.

Their role (Instructor/Student) is retrieved and stored in MongoDB.

Role-Based Redirect:

Instructor: Can create & save MCQs.

Student: Can view & attempt MCQs.

This README will provide a clear overview of your project on GitHub while making it visually engaging with emojis! 🚀








