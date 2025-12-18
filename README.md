# 💼 Job Portal — Full-Stack Recruitment Management System

Job Portal is a full-stack web application designed to streamline the hiring process by connecting job seekers and recruiters on a single platform.
It provides a secure, scalable, and real-time experience for job applications, company management, and recruitment workflows.

---

## 🚀 Live Demo

| Component | Link |
|------------|------|
|🧠 **Backend (API Server)** | [https://job-portal-full-stack-server-gilt.vercel.app](https://job-portal-full-stack-server-gilt.vercel.app)|
|💻 **Frontend (User Portal)** | [https://job-portal-full-stack-client-woad.vercel.app](https://job-portal-full-stack-client-woad.vercel.app)|

---

## 🧩 Features

### 👥 User-Side (Job Seeker)
- Secure authentication & authorization
- Browse and search job listings
- Filter jobs by role, location, and category
- Apply for jobs with resume upload
- View applied jobs and application status
- Update user profile

### 🧑‍💼 Recruiter / Admin
- Recruiter authentication
- Create and manage companies
- Post, update, and delete job listings
- View applicants for each job
- Update applicant status (Pending / Accepted / Rejected)
- Secure access to admin routes

### ⚙️ Backend (Node.js + Express)
- RESTful API architecture
- MongoDB Atlas cloud database
- JWT-based authentication
- File uploads using Cloudinary
- Role-based access control (User / Recruiter)
- Production-ready API deployment

---

## 🛠️ Tech Stack

|Layer | Technologies|
|-------|---------------|
| **Frontend** | React, Vite, Tailwind CSS, Redux Toolkit, Axios|
| **Backend** | Node.js, Express.js|
| **Database** | MongoDB Atlas|
| **Authentication** | JSON Web Tokens (JWT), Clerk|
| **Cloud & Storage** | Cloudinary|
| **Deployment** | Vercel (Frontend), Render / Serverless (Backend)|

---

## 🔒 Environment Variables (Sample)

⚠️ Never commit real secrets to GitHub.

```env
# Backend (`backend/.env`)
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret

CLERK_WEBHOOK_SECRET=your_clerk_webhook_secret
CLERK_SECRET_KEY=your_clerk_secret_key

# Frontend (client/.env)
VITE_BACKEND_URL=https://job-portal-full-stack-server-gilt.vercel.app
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key

```

## 🏗️ Project Structure

```env
Job-Portal-Full-Stack/
│
├── backend/          # Node.js + Express API
│   ├── config/       # DB, Cloudinary, Clerk config
│   ├── controllers/  # Business logic
│   ├── models/       # MongoDB schemas
│   ├── routes/       # API routes
│   └── index.js
│
├── client/           # User-facing frontend (React + Vite)
│   ├── src/
│   └── public/
│
└── README.md

```

## 🚀 Deployment Overview

- **Backend** hosted on **Render / Serverless** — exposes REST APIs
- **Frontend** hosted on **Vercel** — optimized for production builds
- **Environment variables** securely configured per platform
- **MongoDB Atlas** used for cloud database
- **CORS** enabled for frontend-backend communication

---

## 🎯 Learning Outcomes

- Full MERN stack application architecture
- Secure authentication & authorization
- Real-world CRUD workflows
- File uploads & cloud storage integration
- Redux Toolkit for scalable state management
- Production deployment & environment configuration

---

## 👩‍💻 Author

**Rishabh Raj**  
B.Tech Computer Science & Engineering | KIIT University  
📍 Patna, India  

🌐 [GitHub](https://github.com/rishabhraj04)  
🔗 [LinkedIn](https://www.linkedin.com/in/rishabhraj04)

---

## 🌱 Future Enhancements

- Email notifications for job applications
- Pagination & performance optimization
- Resume parsing & skill matching
- Admin analytics dashboard
- Role-based permissions expansion

---

## 🙌 Acknowledgement

This project was developed as part of a full-stack learning and deployment initiative, demonstrating end-to-end development, secure authentication, cloud integration, and real-world recruitment workflows using the MERN stack.

---