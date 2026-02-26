# Skill Swap Hub Backend

Backend API for **Skill Swap Hub**, a platform where users can exchange skills, connect, and collaborate.  
Built with **Node.js, Express, and MongoDB**.

---

## 🚀 Features
- User authentication (signup/login with JWT)
- Skill management (add, update, delete, list skills)
- Secure API routes with middleware
- MongoDB integration for persistent storage
- Structured controllers and routes for scalability

---

## 🛠️ Tech Stack
- **Node.js** – runtime environment
- **Express.js** – web framework
- **MongoDB + Mongoose** – database
- **JWT** – authentication
- **dotenv** – environment configuration

---

## 📂 Project Structure
skill-swap-hub-backend/ │── config/       
# Database connection │── controllers/    
# Business logic │── middleware/   
# Authentication & validation │── models/      
# Mongoose schemas │── routes/      
# API endpoints │── server.js        
# Entry point │── .env          
# Environment variables


---

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/roshankumar8368/skill-swap-hub-backend.git
   cd skill-swap-hub-backend
2. Install dependencies:
  npm install
- Create a .env file in the root with:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key


- Start the server:
npm start


- or with nodemon:
npm run dev



🔗 API Endpoints
Auth
- POST /api/auth/signup → Register new user
- POST /api/auth/login → Login user
Skills
- GET /api/skills → Get all skills
- POST /api/skills → Add new skill
- PUT /api/skills/:id → Update skill
- DELETE /api/skills/:id → Delete skill

🌐 Full-Stack Project Links
- Frontend Repo → skill-swap-hub
- Backend Repo → skill-swap-hub-backend

📌 Future Improvements
- Real-time chat integration
- Role-based access control
- Deployment on cloud (Heroku/Render + MongoDB Atlas)

👨‍💻 Author
Roshan Kumar
Second-year BCA student | Full-stack developer 

---
