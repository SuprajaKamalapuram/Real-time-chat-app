# 💬 Full Stack Realtime Chat App

A modern full-stack real-time chat application with authentication, live messaging, and online user tracking.

---

## 🚀 Tech Stack

- **Frontend:** React.js, TailwindCSS, DaisyUI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Realtime:** Socket.io
- **State Management:** Zustand
- **Authentication:** JWT (JSON Web Tokens)
- **Deployment:** Render

---

## ✨ Features

- 🔐 User Authentication & Authorization (JWT)
- 💬 Real-time messaging with Socket.io
- 🟢 Online/offline user status
- 📦 Global state management with Zustand
- ⚡ Fast and responsive UI
- 🛡️ Error handling (client + server)

---

## 📁 Project Setup

### 1️⃣ Clone the repository

```bash
git clone <your-repo-url>
cd <your-project-folder>
```

2️⃣ Setup Environment Variables

Create a .env file in the backend folder:
```bash
MONGODB_URI=your_mongodb_uri
PORT=5001
JWT_SECRET=your_secret_key

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

NODE_ENV=development
```

3️⃣ Install Dependencies
```bash
npm install
```

4️⃣ Build Frontend
```bash
npm run build
```

5️⃣ Run the App
```bash
npm start
```

🌐 Deployment

The app is deployed on Render.  

Make sure to update environment variables in production.  

---

⚠️ Important Notes  

* Ensure MongoDB is running or use MongoDB Atlas  
* Update CORS settings for production  
* Keep your .env file secure (never commit it)  

🙌 Acknowledgements

This project was built as part of learning and improving full-stack development skills.
