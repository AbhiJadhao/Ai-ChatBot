# Ai-ChatBot
AI-SaaS Chat Bot
AI-SaaS Chat Bot is a web application that allows users to interact with an AI-powered chatbot. The chatbot can respond to user messages and provide assistance based on the input provided.
Features
User authentication (login and signup)
Chat interface with message history
AI-powered responses using OpenAI API
Responsive design using Tailwind CSS
Sidebar for chat history
Logout functionality
Technologies Used
Frontend: React, Tailwind CSS, Axios, GSAP
Backend: Node.js, Express, MongoDB, Mongoose, JWT, OpenAI API
Installation
Clone the repository:

git clone https://github.com/AbhiJadhao/AI-SaaS-Chat-Bot.git
cd AI-SaaS-Chat-Bot
Install dependencies for the backend:

cd Backend
npm install
Install dependencies for the frontend:

cd ../Frontend
npm install
Create a .env file in the Backend folder and add the following environment variables:

PORT=4000
DB_CONNECT="your-mongodb-connection-string"
JWT_SECRET="your-jwt-secret"
OPEN_AI_SECRET="your-openai-api-key"
OPENAI_ORGANIZATION_ID="your-openai-organization-id"
Usage
Start the backend server:

cd Backend
npm start
Start the frontend development server:

cd ../Frontend
npm start
Open your browser and navigate to http://localhost:3000 to access the application.

Project Structure
AI-SaaS-Chat-Bot/
├── Backend/
│   ├── config/
│   │   └── openai.config.js
│   ├── controllers/
│   │   └── chat.controller.js
│   ├── middleware/
│   │   └── authMiddleware.js
│   ├── models/
│   │   └── user.model.js
│   ├── routers/
│   │   └── chat.routes.js
│   ├── services/
│   │   └── chat.services.js
│   ├── .env
│   ├── app.js
│   └── server.js
├── Frontend/
│   ├── src/
│   │   ├── components/
│   │   │   └── Header.jsx
│   │   ├── context/
│   │   │   └── AuthContext.js
│   │   ├── pages/
│   │   │   ├── Chat.jsx
│   │   │   ├── Home.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── NotFound.jsx
│   │   │   ├── SignUp.jsx
│   │   │   └── Start.jsx
│   │   ├── App.jsx
│   │   └── index.js
│   ├── public/
│   └── package.json
├── README.md
└── package.json
License
This project is licensed under the MIT License
