# 🧑‍💼 Job Portal — MERN Application

A full-stack job-management platform built using the MERN stack (MongoDB, Express, React, Node).  
Users can register, log in, create/update/delete job listings, and manage personal profiles.

---

## 🚀 Features

### 🔐 Auth
- User Registration
- Login with JWT
- Protected routes
- Role-based access (if enabled)

### 👤 User
- Update profile
- See personal job posts
- Apply / track jobs (optional depending on implementation)

### 💼 Jobs
- Create job post
- Edit job post
- Delete job post
- List available jobs
- Filter / search (if implemented)

---

## 🏗️ Tech Stack

| Layer | Tech |
|-------|------|
| Frontend | React (Vite) |
| Backend | Node + Express |
| Database | MongoDB (Mongoose) |
| Auth | JWT |
| State | React State/Context |
| Styling | CSS |


---

## ⚙️ Backend Setup

```bash
cd job/server
npm install
cp .env.example .env   # create your env
npm run dev

PORT=5000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret

cd job/server
node scripts/seed.js

cd job/client
npm install
npm run dev
