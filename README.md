# 💰 AI Finance SaaS Platform

An advanced **MERN-based SaaS application** that helps users track, analyze, and optimize their finances using AI-powered insights.

---

## 🧠 Overview

This platform allows users to manage income and expenses, gain deep financial insights through analytics, and automate reports — all in a modern, scalable SaaS architecture.

Built with a focus on **real-world production practices**, including authentication, data pipelines, background jobs, and cloud integrations.

---

## ✨ Key Features

* 🔐 Secure Authentication (JWT-based login/signup)
* 🏢 Create, Edit & Manage Transactions
* 📤 AI-Powered Receipt Upload & Scanning
* 📈 Advanced Analytics (MongoDB Aggregation Pipeline)
* 📊 Expense Breakdown (Pie Chart)
* 📉 Income vs Expense Trends (Line Chart)
* 📅 Smart Date Filtering (Last 7 / 30 Days, Custom Range)
* ♻️ Recurring Transactions (Cron Jobs)
* 📄 Auto-Generated Monthly Reports (Email Integration)
* 📥 CSV Import for Bulk Transactions
* 🔍 Search & Advanced Filtering
* 📅 Pagination for Scalability
* 🗑️ Bulk Delete & Duplicate Transactions
* 🧑‍💼 Profile Photo Upload (Cloudinary)

---

## 🏗️ Tech Stack

### Frontend

* React.js
* TypeScript
* Tailwind CSS (or your UI library)

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)

### Other Tools & Services

* JWT Authentication
* Cloudinary (Image Uploads)
* Cron Jobs (Background Tasks)
* Nodemailer (Email Reports)
* MongoDB Aggregation Pipeline
* CSV Parser

---

## 📁 Project Structure

```
finance-saas-platform/
│
├── client/        # Frontend (React + TypeScript)
├── server/        # Backend (Node.js + Express)
├── docs/          # Documentation / API Notes
├── .env.example   # Environment variables template
├── README.md
```

---

## ⚙️ Setup Instructions

### 1. Clone the repository

```
git clone git@github.com:rushilsatwara73/finance-saas-platform.git
cd finance-saas-platform
```

### 2. Install dependencies

#### Backend

```
cd server
npm install
```

#### Frontend

```
cd client
npm install
```

---

### 3. Environment Variables

Create a `.env` file in the **server** folder and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_key
CLOUDINARY_API_SECRET=your_secret
EMAIL_USER=your_email
EMAIL_PASS=your_password
```

---

### 4. Run the project

#### Backend

```
cd server
npm run dev
```

#### Frontend

```
cd client
npm start
```

---

## 📊 Future Improvements

* 🤖 AI-based financial insights & recommendations
* 📱 Mobile responsiveness optimization
* 🔔 Real-time notifications
* 💳 Payment gateway integration (Stripe/Razorpay)
* 📈 Predictive expense analysis

---

## 📌 Use Case

This project demonstrates:

* Full-stack development (MERN)
* SaaS architecture design
* Real-world backend engineering
* Data analytics using MongoDB
* Integration of third-party services

---

## 🧑‍💻 Author

**Rushil Satwara**

---

## ⭐ Contribute / Support

If you like this project, consider giving it a ⭐ on GitHub!
Feel free to fork the repository and submit pull requests for improvements or new features!
