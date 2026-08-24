# 🤖 Automate AI

An AI-powered virtual assistant built using the MERN Stack and Google's Gemini API. Automate AI allows users to interact with an intelligent chatbot capable of answering questions, providing assistance, and generating AI-powered responses through a clean and responsive web interface.    
 
---  

## 🚀 Features

- 🔐 User Authentication (Sign Up & Login)
- 🤖 AI-powered conversations using Google Gemini API    
- 💬 Real-time chat interface
- ☁️ Cloudinary integration for media management 
- 📱 Fully responsive user interface
- 🔒 Secure authentication using JWT
- 💾 MongoDB database for user and chat data
- ⚡ Fast and scalable backend with Express.js
- 🎨 Modern React-based frontend 

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Vite
- HTML5
- CSS3
- JavaScript (ES6+)

### Backend
- Node.js
- Express.js

### Database
- MongoDB Atlas
- Mongoose

### Authentication
- JSON Web Token (JWT)

### APIs & Services
- Google Gemini API
- Cloudinary

### Development Tools
- Git
- GitHub
- VS Code
- Postman

---

## 📂 Project Structure

```
Automate-AI/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── public/
│   ├── routes/
│   ├── index.js
│   ├── gemini.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── index.html
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/ManasDeveshTrivedi/Automate-AI.git
```

Move into the project directory

```bash
cd Automate-AI
```

---

## 📦 Backend Setup

Navigate to backend

```bash
cd backend
```

Install dependencies

```bash
npm install
```

Create a `.env` file inside the backend folder.

Example:

```env
PORT=8000

MONGODB_URL=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

GEMINI_API_URL=your_gemini_api_endpoint
```

Start backend

```bash
npm start
```

or

```bash
npm run dev
```

---

## 💻 Frontend Setup

Navigate to frontend

```bash
cd frontend
```

Install dependencies

```bash
npm install
```

Start development server

```bash
npm run dev
```

---

## 🌐 Environment Variables

| Variable | Description |
|-----------|-------------|
| PORT | Backend server port |
| MONGODB_URL | MongoDB Atlas Connection String |
| JWT_SECRET | Secret key for JWT authentication |
| CLOUDINARY_CLOUD_NAME | Cloudinary cloud name |
| CLOUDINARY_API_KEY | Cloudinary API key |
| CLOUDINARY_API_SECRET | Cloudinary API secret |
| GEMINI_API_URL | Google Gemini API endpoint |

---

## 🔒 Authentication Flow

- User Registration
- User Login
- JWT Token Generation
- Protected Routes
- Secure API Access

---

## 📡 API Overview

### Authentication

- Register User
- Login User

### AI

- Generate AI Responses

### User

- Get User Details
- Update User Information

---

## 🚀 Future Enhancements

- Voice Assistant Support
- Speech-to-Text
- Text-to-Speech
- Chat History
- Multiple AI Models
- Theme Customization
- Image Generation
- File Upload Support
- Conversation Export
- Multi-language Support
