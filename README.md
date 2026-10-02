# 🚀 Placement Preparation Platform

An AI-powered Placement Preparation Platform designed to help students prepare for campus placements through resume analysis, ATS optimization, skill gap detection, and personalized interview preparation. The platform leverages Google's Gemini AI to provide intelligent insights and recommendations for improving placement readiness.

---

## 📌 Features

### 🤖 AI Resume Analysis
- Upload resume in PDF format
- Analyze resume using Gemini AI
- Identify strengths and weaknesses
- Get improvement suggestions

### 📄 ATS Resume Generator
- Generate ATS-friendly resumes
- Improve resume formatting
- Increase compatibility with Applicant Tracking Systems

### 🎯 Skill Gap Detection
- Compare current skills with target job roles
- Identify missing technologies and concepts
- Receive personalized learning recommendations

### 💬 AI Interview Preparation
- Generate role-specific interview questions
- Technical and HR interview practice
- Personalized question recommendations
- AI-generated answers and explanations

### 📊 Dashboard
- Track preparation progress
- Resume improvement history
- Skill development overview

---

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- SCSS
- HTML5
- Axios

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Gemini AI API
- JWT Authentication

---

## 📂 Project Structure

```
Placement_Preparation_Platform
│
├── Frontend/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── Backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/PranjitaModi/Placement_Preparation_Platform.git
cd Placement_Preparation_Platform
```

---

## Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file inside the Backend folder.

Example:

```env
PORT=5000

MONGODB_URI=Your_MongoDB_URI

JWT_SECRET=Your_JWT_Secret

GEMINI_API_KEY=Your_Gemini_API_Key
```

Run backend

```bash
npm start
```

or

```bash
npm run dev
```

---

## Frontend Setup

```bash
cd Frontend
npm install
```

Create a `.env` file

```env
VITE_API_URL=http://localhost:5000
```

Run frontend

```bash
npm run dev
```

---

## 📷 Application Workflow

1. User creates an account/login.
2. Uploads resume.
3. AI analyzes the resume.
4. ATS score and improvement suggestions are generated.
5. Skill gaps are identified.
6. Personalized interview questions are generated.
7. User tracks placement preparation progress.

---

## 🔒 Environment Variables

Backend

```
PORT

MONGODB_URI

JWT_SECRET

GEMINI_API_KEY
```

Frontend

```
VITE_API_URL
```

---

## 🚀 Future Enhancements

- Company-wise coding questions
- Online coding compiler
- Mock interview with voice AI
- Placement roadmap generator
- Company eligibility checker
- Resume version management
- Placement analytics dashboard
- Email notifications
- Admin dashboard

---

## 👩‍💻 Author

**Pranjita Modi**

B.Tech CSE (AI & DS)

Full Stack Developer

GitHub: https://github.com/PranjitaModi

---

## 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub to support the project.
