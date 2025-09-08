# 🤖 QuickGPT – Smart AI Assistant
🌐 **Live Demo**: https://quick-gpt-one.vercel.app/

## Overview
QuickGPT is a full-stack AI platform that combines intelligent conversations with creative image generation. Powered by Google Gemini for natural text responses and ImageKit.io for stunning visuals, it delivers a seamless AI experience. The app runs on a credit-based system, where users can generate chats and images while managing their usage through Stripe-powered subscription plans. With secure JWT authentication, MongoDB for chat history, and a modern React + TailwindCSS interface, QuickGPT offers a polished, scalable, and engaging AI workspace.
---

## ✨ Key Features

- 🔐 **Secure authentication with JWT and password hashing using bcryptjs**
- 🔒 **Middleware-protected API routes for safe user access**
- 💬 **AI text responses powered by Google Gemini**
- 📝 **Persistent chat history with user/assistant roles**
- 🎨 **AI-generated images using ImageKit.io, hosted on CDN**
- 🌍 **Option to publish images for community sharing**
- 📂 **Full chat management: create, view, delete, and sort by activity**
- 👤 **User Dashboard – View your own generated content**
- 💵 **Flexible subscription plans via Stripe (Basic, Pro, Premium)**
- ⚡ **Modern UI with React + Vite + TailwindCSS**
- 🚀 **Deployed on Vercel**

## 🛠️ Tech Stack

### Frontend:
- **React.js**
- **Tailwind CSS**
- **react-hot-toast**
- **Axios**
- **PrismJS**
- **react-markdown**
- **Vercel** (Deployment)

### Backend:
- **Node.js**
- **Express.js**
- **MongoDB (Mongoose)**
- **JWT**
- **bcryptjs**
- **Svix**
- **CORS**
- **Stripe**

### AI Services
- **Google Gemini (text)**
- **ImageKit.io (images)**

---


## 📦 Installation & Setup (Local Development)

# Clone the repository
git https://github.com/deepesh2596/QuickGPT
cd client

# Install dependencies for backend
cd server
npm install

# Example .env content (create .env using your credentials)

## **Frontend .env**
- VITE_BASE_URL=http://localhost:3000 (your backend url)

## **Backend .env**
- JWT_SECRET= your_jwt_secret
- MONGODB_URI= your_mongodb_connection_string
- GEMINI_API_KEY= your_gemini_api_key
- IMAGEKIT_PUBLIC_KEY= your_imagekit_public_key
- IMAGEKIT_PRIVATE_KEY= your_imagekit_private_key
- IMAGEKIT_URL_ENDPOINT= your_imagekit_url
- STRIPE_PUBLISHABLE_KEY= your_stripe_pubishable_key
- STRIPE_SECRET_KEY= your_stripe_secret
- STRIPE_WEBHOOK_SECRET= your_webhook_secret

### 🚀 Usage Flow
- **Register/Login** -> Create an account
- **Start a Chat** -> Create new chat session
- **Send Prompt** -> Generate AI text or images
- **Publish Images** -> Make generated images public
- **Manage Chats** -> Continue or delete chats
- **Purchase Credits** -> Buy plans using Stripe checkout

# Start backend server
npm run server

# Go to frontend
cd ../client
npm install

# Start frontend
npm run dev

---


🤝 Contributing

**Contributions are always welcome!**
- Fork this repository
- Create a new branch (git checkout -b feature/NewFeature)
- Commit your changes (git commit -m 'Add New Feature')
- Push to your branch (git push origin feature/NewFeature)
- Open a Pull Request

📬 Contact
- Developer: Deepesh Chauhan
- Email: deepesh2596@gmail.com
- LinkedIn: linkedin.com/in/deepesh-chauhan
 


**It’s deployed live and ready to use — give it a try!**


