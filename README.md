🌟 Instagram Clone – MERN Stack (React, Node, MongoDB, TailwindCSS)

A full-stack Instagram clone built using MERN stack with:

🔐 Authentication (JWT)

📝 Create Posts

❤️ Like / Unlike

💬 Comments

👤 Profile Page (Followers, Following, Posts)

🖼️ Instagram-style UI using TailwindCSS

📱 Fully Responsive

🌐 REST APIs

📂 Project Structure
123/task/

│── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
└── frontend/
    ├── src/
    ├── public/
    ├── package.json
    └── tailwind.config.js

⚙️ Tech Stack
Frontend

React + Vite

Tailwind CSS

Axios

Zustand (state management)

Backend

Node.js + Express.js

MongoDB + Mongoose

JWT Authentication

BcryptJS

🛠️ Features
🔐 Authentication

Signup / Login

JWT-based auth

Protected routes

📝 Posts

Upload image

Add caption

Instagram-like UI

❤️ Interactions

Like / Unlike post

Comment on posts

👤 User Profile

Profile Picture layout

Followers / Following

User posts grid

Edit profile button (UI)

📱 Responsive UI

Mobile-friendly

Looks similar to original Instagram

🧩 Backend Setup
📌 1. Navigate to backend folder
cd backend

📌 2. Install dependencies
npm install

📌 3. Create .env file
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret
PORT=5000

📌 4. Start backend server
npm run dev


Backend will run on:

👉 http://localhost:5000

🎨 Frontend Setup
📌 1. Navigate to frontend folder
cd frontend

📌 2. Install dependencies
npm install

📌 3. Start React app
npm run dev


Frontend will run on:

👉 http://localhost:5173

🔗 API Endpoints
Auth
Method	Endpoint	Description
POST	/api/auth/signup	Create account
POST	/api/auth/login	Login
Posts
Method	Endpoint	Description
POST	/api/posts	Create post
GET	/api/posts/feed	Get feed posts
POST	/api/posts/:id/like	Like post
POST	/api/posts/:id/comment	Comment on post
Profile
Method	Endpoint	Description
GET	/api/profile/me	Get logged-in user profile
GET	/api/profile/me/posts	Get logged-in user posts
🎯 How to Run Full MERN App
▶ Step 1: Start Backend
cd backend
npm run dev

▶ Step 2: Start Frontend
cd frontend
npm run dev

▶ Step 3: Open your browser
http://localhost:5173
