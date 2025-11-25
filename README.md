SignBridge – ISL Learning System 🤟🎓

SignBridge is an EdTech-focused AI system that helps learners understand and practice Indian Sign Language (ISL) using real-time gesture recognition, interactive animations, and audio/video–based ISL learning tools.

This project promotes inclusive education, making ISL learning accessible for students, teachers, and peers.

🚀 Features:

🤟 ISL → Text recognition using webcam

🔊 Audio → ISL animation output

🎥 Video → ISL gesture translation

👐 Real-time gesture tracking (MediaPipe)

⚡ Fast & lightweight React (Vite) frontend

🌐 Backend API deployed on Render

🖥️ Frontend Setup:

1.cd client

2.npm install

3.npm run dev


Local URL:
http://localhost:5173/

🔗 Backend Setup:

The backend is already deployed.

Add this to your frontend .env file:
VITE_API_BASE_URL=https://signbridgebackend-g6zh.onrender.com

🧠 How It Works:

ISL → Text

User enables webcam

Frames are sent to backend

MediaPipe extracts hand landmarks

ML model predicts the ISL gesture

Text appears instantly in the UI

Audio/Video → ISL

Audio/Video → converted to speech-to-text

Text mapped to ISL vocabulary

Matching ISL animation displayed
