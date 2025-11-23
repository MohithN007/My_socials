Social Activity Feed

A social activity feed web application  featuring user authentication, posts, likes, follows, and an activity wall.
Built using React + Tailwind CSS for frontend and Node.js + Express + MongoDB Atlas for backend.

🔗 Live Demo

Frontend (Vercel): [https://<your-frontend-url>](https://inkle-assigment-project.vercel.app/)

Backend (Render): [https://<your-backend-url>/api](https://inkle-assigment-project.onrender.com)

🛠 Technologies Used
Layer	Technology
Frontend	React, Vite, Tailwind CSS, Axios
Backend	Node.js, Express.js, MongoDB Atlas, Mongoose, JWT, bcrypt
Deployment	Vercel (frontend), Render (backend)
Authentication	JWT (JSON Web Tokens)
API	RESTful endpoints
💡 Features

User Management

Signup / Login / JWT-based authentication

Block other users (blocked user’s posts are hidden)

Admins: can delete users, posts, likes

Posts & Interactions

Create posts

Like/unlike posts

Follow/unfollow other users

Activity Feed

Shows activities of all users in the network





Setup Instructions (Local Dev)

Clone repo

git clone https://github.com/MohithN007/inkle_assigment_project.git
cd inkle_assigment_project


Backend

cd backend
npm install
cp .env.example .env      # set your MongoDB Atlas URI & JWT_SECRET
npm run dev               # or node server.js


Frontend

cd ../frontend
npm install
cp .env.local.example .env.local   # set VITE_API_URL
npm run dev


Visit http://localhost:5173 and test the app.

🚀 Deployment

Backend: Render → backend folder → add environment variables (MONGO_URI, JWT_SECRET) → deploy

Frontend: Vercel → frontend folder → add VITE_API_URL pointing to Render backend → deploy



Key Learnings

Full-stack development with Node.js, Express, MongoDB Atlas, React, Tailwind

JWT authentication & role-based permissions

Activity feed design & logging

Environment variable handling for dev & production

Deployment workflow with Render & Vercel
