# 🤟 SignBridge – Inclusive ISL Learning Platform

**SignBridge** is an AI-powered inclusive education tool designed to help learners practice and understand **Indian Sign Language (ISL)**.  
It enables students, teachers, and peers to learn ISL through real-time gesture recognition, audio/video-based ISL animations, and interactive learning modules.

---

## 📌 Features

- 🤟 ISL → Text recognition using webcam  
- 🔊 Audio → ISL animation output  
- 🎥 Video → ISL gesture translation  
- 👐 Real-time gesture tracking (MediaPipe)  
- ⚡ Fast & lightweight React (Vite) frontend  
- 🌐 Backend API deployed on Render  
- 🎓 Built for inclusive ISL education & learning

---

## 🧠 Tech Stack

### 🔙 Backend
- Node.js / Python (model inference & APIs)
- Custom ISL recognition ML model  
- Speech-to-text pipeline for audio/video processing  
- Quiz generation module  
- Hosted on Render

### 🌐 Frontend
- React + Vite  
- Tailwind CSS  
- Framer Motion  
- MediaPipe (Hand Tracking)  
- Axios for API communication  

---

## 🎓 Educational Purpose

SignBridge promotes **inclusive learning** by offering:  
- Real-time ISL practice  
- Audio/video-based ISL learning  
- Interactive animations  
- Assisted ISL comprehension for classrooms and peer learning

---

## 🧠 How It Works

### ISL → Text
1. Webcam feed activated  
2. Frames sent to backend  
3. MediaPipe extracts hand landmarks  
4. ML model predicts gesture  
5. UI displays recognized text  

### Audio/Video → ISL
1. Extract speech → convert to text  
2. Text mapped to ISL vocabulary  
3. UI displays ISL animation  

---
## 🖥️ Frontend Setup

```bash
cd client
npm install
npm run dev

Local URL:  
http://localhost:5173/
```
---

## 🔗 Backend Setup

Backend is already deployed.

Add this in your `client/.env` file:

VITE_API_BASE_URL=https://signbridgebackend-g6zh.onrender.com

