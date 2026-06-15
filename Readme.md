# AI-Powered Interview Platform

An **AI-driven mock interview platform** leveraging **Azure AI** (Speech-to-Text) and **Gemini AI** (for intelligent question generation). Built with **MERN stack** and deployed using **AWS Serverless** for a **scalable and cost-efficient** backend.

## 🚀 Features
- **AI-Powered Question Generation** – Uses **Gemini AI** to generate dynamic, role-specific interview questions.
- **Real-time Transcription** – Converts speech to text via **Azure AI Speech Services** for seamless interview documentation.
- **Scalable & Serverless** – Deployed with **AWS Lambda and API Gateway** for optimal performance.
- **Interactive Code Editor** – Supports live coding assessments

---

## 🛠️ Tech Stack
### **Frontend (Client)**
- **React.js + Vite** – Fast and optimized UI
- **Tailwind CSS** – Modern, responsive styling
- **Lucide React** – Icon library for enhanced UI

### **Backend (Server)**
- **Node.js & Express.js** – Efficient REST API backend
- **MongoDB (Atlas)** – Cloud database for structured interview data
- **AWS Serverless** – Lambda, API Gateway, and S3 for scalable deployment
- **Socket.io** – Real-time communication for interview sessions
- **Azure AI Speech-to-Text** – Converts spoken words to text in real time
- **Gemini AI** – Generates interview questions dynamically

---

## 📂 Folder Structure
```
📦 AI-Interview-Platform
├── 📁 client   # Frontend (React + Vite)
├── 📁 server   # Backend (Node.js + Express)
└── README.md
```

---

## 🔧 Setup Instructions

### 1️⃣ Clone the Repository
```sh
git clone hhttps://github.com/Cleveridiot07/MockMate.git
cd= mockmate
```

### 2️⃣ Setup **Client** (Frontend)
```sh
cd client
npm install
npm run dev  # Starts frontend on http://localhost:5173
```

### 3️⃣ Setup **Server** (Backend)
```sh
cd server
npm install
npm run dev  # Starts backend on http://localhost:8000
```

---

## 🚀 Deployment
### **Frontend**: Deployed on **Netlify**
```sh
npm run build  # Generates optimized build files
```

### **Backend**: Deployed on **AWS Lambda** via **Serverless Framework**
```sh
serverless deploy
```

---



Pull requests are welcome! 🚀
