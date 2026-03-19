🎓 Curriculum AI Assistant

A full-stack educational platform powered by AI for automated curriculum generation and teaching support.

✨ Overview

Curriculum AI Assistant helps educators streamline their workflow by leveraging AI to:

Generate lesson plans automatically

Create quizzes and assignments

Recommend personalized content

Export materials in multiple formats

🚀 Features
🧠 AI-Powered Content Generation

Automated lesson plan generation

Quiz creation with multiple question types

Homework assignment generation

Smart content recommendations

📄 Document Management

Export materials to PDF

Export materials to DOCX

Customizable templates for lesson plans

👥 User Management

Secure authentication system

User roles & permissions

Profile management

💻 Tech Stack
Layer	Technology Stack
Frontend	React.js, Vite, Material-UI, React Router DOM, Axios
Backend	Node.js, Express.js, MongoDB, JWT Authentication, Google Gemini AI API
📋 Prerequisites

Before running the project, ensure you have:

Node.js (v14 or higher)

MongoDB installed & running

npm or yarn

🛠️ Installation & Setup
1. Clone the Repository
git clone <your-repo-url>
cd curriculum-ai-assistant

2. Backend Setup
cd backend
npm install


Create a .env file in the backend directory:

PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key

3. Frontend Setup
cd frontend
npm install


Create a .env file in the frontend directory:

VITE_API_URL=http://localhost:5000

🚀 Running the Application
Start Backend Server
cd backend
npm run dev

Start Frontend Server
cd frontend
npm run dev


🔗 Application runs at: http://localhost:5173

📡 API Endpoints
🔑 Authentication

POST /api/auth/signup → Register a new user

POST /api/auth/login → Login existing user

🤖 AI Services

POST /api/ai/lesson-plan → Generate a lesson plan

POST /api/ai/quiz → Generate a quiz

POST /api/ai/homework → Generate homework
