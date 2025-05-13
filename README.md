# 🛡️ Secure Notes – Full Stack Application

A secure, full-featured note-taking web application built with **Spring Boot** (backend) and **React.js** (frontend). Users can register, log in via **JWT or GitHub OAuth2**, create and manage encrypted notes, receive email reminders, and control their accounts — all through a responsive and modern interface.

> 🔴 **Note:** The backend is hosted on free-tier services. You might experience a slight delay due to cold start times when first opening the app.

---

## 🌐 Live Demo

🔗 **App:** [https://secure-notes-app-01.netlify.app](https://secure-notes-app-01.netlify.app)  
📄 **API Docs:** [https://surya00011.github.io/secure-notes-api-docs/](https://surya00011.github.io/secure-notes-api-docs/)

---

## 📦 Tech Stack

### 🔧 Backend
- Java 17 + Spring Boot
- Spring Security (JWT & OAuth2)
- MySQL (hosted on Neon.tech)
- JavaMailSender for email services
- ReDoc for API documentation

### 🎨 Frontend
- React.js
- React Router
- Axios
- Tailwind CSS + Material UI + Bootstrap

---

## 🔐 Features

### 🧑‍💼 Authentication & Security
- OAuth2 login via GitHub
- JWT-based login and session control
- OTP-based email verification
- Secure password reset via email token
- Account deletion

### 📩 Email Notifications
- OTP verification for signup/reset
- Deadline-based reminders for notes

### 📝 Notes Management
- Create, update, delete, and view personal notes
- Deadline option for each note
- End-to-end encryption

### 📄 API Documentation
- Fully documented using Swagger-style ReDoc  
  [View API Docs](https://surya00011.github.io/secure-notes-api-docs/)

---
