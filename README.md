# 🎨 Imagify — AI Image Generator

Imagify is a full-stack AI-powered image generation web application that allows users to create stunning images from text prompts. It features user authentication, credit-based image generation, and a modern responsive UI.

The project is built with a React frontend and a Node.js + Express backend, integrating AI APIs for real-time image creation.

---

## ✨ Features

- 🔐 User authentication (Signup / Login)
- 🖼️ AI image generation from text prompts
- ⭐ Credit-based image generation system
- 📥 Download generated images
- 📱 Fully responsive UI
- 🧾 User profile & transaction tracking
- ⚡ Fast frontend using Vite + React
- 🌐 RESTful backend with Express

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- Tailwind CSS
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication

---

## 📂 Project Structure

imagify/
├ client/ # Frontend
└ server/ # Backend

---

## ⚙️ Environment Variables

This project uses **two `.env` files** (not pushed to GitHub):

server/.env : 
JWT_SECRET = "YOUR_SECRET"|
MONGODB_URI = 'YOUR_MONGODB_URL'|
CLIPDROP_API = 'YOUR_CLIPDROP_API'|
CURRENCY ='INR'|
RAZORPAY_KEY_ID = 'YOUR_KEY_ID'|
RAZORPAY_KEY_SECRET = 'YOUR_KEY_SECRET'|
STRIPE_SECRET_KEY = "YOUR_SECRET_KEY"

client/.env :
VITE_BACKEND_URL = 'http://localhost:4000'|
VITE_RAZORPAY_KEY_ID = "YOUR_KEY_ID"

## ▶ Run Locally

### Server

cd server |
npm install |
npm run server 

### Client

cd client |
npm install |
npm run dev 
