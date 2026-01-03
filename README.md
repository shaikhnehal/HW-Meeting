📹 HW Meeting

HW Meeting is a full-stack video meeting web application that allows users to connect with others through online meetings.
It supports user authentication, guest access, and a modern responsive UI.

🌐 Live Demo:
👉 https://hw-meeting-1.onrender.com

🚀 Features

🔐 User Authentication (Register / Login)

👤 Join as Guest

📹 Video Meeting Interface

🌐 Frontend deployed online

🎨 Responsive UI with modern design

🔒 Protected routes using Auth Context

⚙️ Environment-based configuration

🛠️ Tech Stack
Frontend

React.js

CSS

Context API

Axios

Backend

Node.js

Express.js

MongoDB

Mongoose

JWT Authentication

Tools & Platforms

Git & GitHub

Render (Deployment)

📁 Project Structure
HW-Meeting/
│
├── frontend/
│   ├── public/
│   └── src/
│       ├── contexts/
│       ├── pages/
│       ├── styles/
│       ├── utils/
│       └── environment.js
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── server.js
│
├── .gitignore
├── README.md
└── package.json

⚙️ Environment Setup
Frontend (frontend/src/environment.js)
const server = "https://your-backend-url.onrender.com";
export default server;

Backend (backend/.env)
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

▶️ Run Locally
1️⃣ Clone Repository
git clone https://github.com/shaikhnehal/HW-Meeting.git
cd HW-Meeting

2️⃣ Backend Setup
cd backend
npm install
npm start

3️⃣ Frontend Setup
cd frontend
npm install
npm start

📸 Screenshots

Landing Page

Authentication Pages

Video Meeting Interface

(Deployed version available online)

🧠 Learnings

Full-stack project structure

React Context for authentication

Environment handling

Deployment using Render

Git & GitHub workflow

👨‍💻 Author

Shaikh Nehal

GitHub: https://github.com/shaikhnehal
