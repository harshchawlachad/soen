# 💬 AI-Powered Realtime Chat App (MERN + Google Gemini)

A fully functional real-time chat application built using the **MERN stack (MongoDB, Express, React, Node.js)**, enhanced with **Socket.IO** for real-time messaging and integrated with **Google Gemini AI** for intelligent, context-aware replies. Redis is used for improved backend performance and caching.

---

## 🚀 Features

- 🔒 User authentication (Register/Login)
- 💬 One-on-one and group messaging
- ⚡ Real-time chat with Socket.IO
- 🧠 Google Gemini API integration for AI responses
- 🧰 Redis caching for performance
- 🎨 React-based responsive frontend
- 📦 Clean modular codebase

---

## 📁 Folder Structure

project-root/
├── client/ # React frontend
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ └── App.js
│ └── package.json
├── server/ # Node.js backend
│ ├── controllers/
│ ├── routes/
│ ├── models/
│ ├── utils/
│ ├── socket.js
│ └── index.js
├── .env
├── README.md
└── package.json


---

## 🔧 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/harshchawlachad/soen.git
cd soen

2. Set Up Backend
bash
Copy
Edit
cd server
npm install

Create a .env file in the server/ directory:

ini
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
REDIS_URL=redis://localhost:6379
GEMINI_API_KEY=your_google_gemini_api_key

Start the server:

bash
Copy
Edit
npm run dev

3. Set Up Frontend

cd ../client
npm install
npm start

🧠 Google Gemini Integration
This project uses the Gemini API from Google to power AI responses inside the chat interface. You’ll need to:

Sign up at https://ai.google.dev/

Create an API key

Add it to your .env as GEMINI_API_KEY


🧪 Testing
Basic manual testing can be done via:

->Creating two users and opening two browser windows

->Sending messages to see real-time updates

->Watching the Gemini AI bot respond to prompts


🛠 Tech Stack
->Layer	Technology
->Frontend	React, Axios
->Backend	Node.js, Express
->Database	MongoDB
->Realtime	Socket.IO
->Caching	Redis
->AI	Google Gemini API
->Auth	JWT

🙋‍♂️ Author
Harsh Chawla
