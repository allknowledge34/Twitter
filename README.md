# 🐦 Twitter – Full Stack Twitter (X) Social Media App

A production-ready full stack social media application built with React Native, Clerk authentication, Express.js, MongoDB, and Cloudinary.

---

![Demo App](/mobile/assets/images/maxresdefault-9.jpg)

---

## 🚀 Overview

Twitter is a modern Twitter (X) inspired mobile application that demonstrates real-world full stack development.

The project covers everything from authentication and media uploads to real-time interactions, backend security, and full deployment workflows.

Designed to simulate a real production social media platform.

---

## ✨ Key Features

🔐 Authentication with Clerk (Google & Apple login)  
🏠 Post text & images (camera + gallery support)  
❤️ Like & comment system with smooth UI  
🔔 Real-time notifications  
📬 Live chat with message history & delete option  
👤 Profile management & editable profile modal  
🔎 Trending search & content discovery  
🚪 Secure sign out flow  
🛠 REST API with Express.js & MongoDB  
☁️ Image upload & hosting via Cloudinary  
🛡 Security layers (rate limiting, bot protection)  
📦 Production deployment workflow  
🧪 GitHub collaboration with branches & PRs  

---

## 🏗 Tech Stack

### 📱 Mobile App
- React Native  

### 🔐 Authentication
- Clerk  

### 🌐 Backend
- Node.js  
- Express.js  

### 🗄 Database
- MongoDB  

### ☁️ Media Storage
- Cloudinary  

### 🛡 Security
- Arcjet protection tools  

---

## 📁 .env Setup

### ⚙️ Backend (`/backend`)

```bash
PORT=5001
NODE_ENV=development

CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>
CLERK_SECRET_KEY=<your_clerk_secret_key>

MONGO_URI=<your_mongodb_connection_uri>

ARCJET_ENV=development
ARCJET_KEY=<your_arcjet_api_key>

CLOUDINARY_CLOUD_NAME=<your_cloudinary_cloud_name>
CLOUDINARY_API_KEY=<your_cloudinary_api_key>
CLOUDINARY_API_SECRET=<your_cloudinary_api_secret>
```
### ⚙️ Mobile (`/mobile`)

```bash
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=<your_clerk_publishable_key>

EXPO_PUBLIC_API_URL=<your_backend_api_url>
```

## ⚙️ Run the backend

```bash
cd backend
npm install
npm run dev

```

## 📱 Run the mobile

```bash
cd mobile
npm install
npx expo start
```
---

## 🎯 Use Cases
✔ Resume projects
✔ Hackathons
✔ AI demos
✔ Full stack practice
✔ Startup MVP

---
## 🤝 Contributing
Contributions are welcome.

---
## ⭐ Support
If you found this project useful, give it a star ⭐
