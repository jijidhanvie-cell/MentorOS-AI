# 🚀 MentorOS AI

> **AI-Powered Personalized Learning Roadmap Generator**

MentorOS AI is an AI-powered web application that generates personalized learning roadmaps based on a user's career goal, skill level, available study time, and preferred learning style. The application uses **Google Gemini AI** to create structured weekly learning plans that help learners stay organized and focused.

---

## 📌 Problem Statement

Students often struggle to decide:

- What should I learn first?
- What topics should I cover each week?
- How can I create a structured learning plan?

MentorOS AI solves this problem by generating an AI-powered personalized roadmap in seconds.

---

# ✨ Features

## ✅ Implemented (v1.0)

- 🤖 AI-generated personalized learning roadmap
- 🎯 Career goal-based roadmap generation
- 📚 Weekly learning plan with tasks
- ⚡ Google Gemini AI integration
- 🌐 FastAPI backend
- 💻 Next.js frontend
- 📊 Interactive dashboard
- 💾 Local Storage support
- 🔄 Frontend–Backend API integration

---

# 🛠️ Tech Stack

### Frontend

- Next.js 16
- React
- TypeScript
- Tailwind CSS

### Backend

- FastAPI
- Python

### AI

- Google Gemini API

### Development Tools

- GitHub Codespaces
- Git
- GitHub

---

# 📂 Project Structure

```
MentorOS-AI
│
├── backend
│   ├── app
│   │   ├── routes
│   │   ├── services
│   │   └── main.py
│   └── requirements.txt
│
├── frontend
│   ├── app
│   ├── components
│   └── package.json
│
├── screenshots
│
└── README.md
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/MentorOS-AI.git
```

---

## Backend

```bash
cd backend

python -m venv venv

source venv/bin/activate

pip install -r requirements.txt

python3 -m uvicorn app.main:app --reload
```

Backend runs on

```
http://localhost:8000
```

---

## Frontend

```bash
cd frontend

npm install

npm run dev
```

Frontend runs on

```
http://localhost:3000
```

---

# 🚀 API Endpoint

## Generate Roadmap

### POST

```
/api/roadmap
```

### Request

```json
{
  "goal": "Cyber Security Engineer",
  "level": "Beginner",
  "dailyHours": 2,
  "learningStyle": "Visual"
}
```

### Response

```json
{
  "goal": "Cyber Security Engineer",
  "weeks": [
    {
      "week": 1,
      "topic": "Networking Fundamentals",
      "tasks": [
        "Learn OSI Model",
        "Understand TCP/IP",
        "Practice Networking Basics"
      ]
    }
  ]
}
```

---

# 📸 Application Screenshots

## Create Plan Page

![Create Plan](screenshots/01-create-plan-page.png)

---

## Roadmap Input Form

![Input Form](screenshots/02-roadmap-input-form.png)

---

## Dashboard Overview

![Dashboard](screenshots/03-dashboard-overview.png)

---

## Weekly Roadmap (Part 1)

![Week 1-3](screenshots/04-weekly-roadmap-1.png)

---

## Weekly Roadmap (Part 2)

![Week 4-5](screenshots/05-weekly-roadmap-2.png)

---

## Weekly Roadmap (Part 3)

![Week 6-7](screenshots/06-weekly-roadmap-3.png)

---

## Final Week

![Week 8](screenshots/07-final-week-roadmap.png)

---

# 🤖 AI Workflow

```
User Input

↓

Frontend (Next.js)

↓

FastAPI Backend

↓

Google Gemini AI

↓

Generated Weekly Roadmap

↓

Dashboard Display
```

---

# 🔮 Future Enhancements

- User Authentication
- Progress Tracking
- Task Completion
- Database Integration
- AI Mentor Chat
- AI Quiz Generator
- PDF Export
- Learning Analytics
- Dark Mode
- Notifications
- Multi-user Support

---

# 👥 Team

| Name | Role |
|------|------|
| Team Lead     | Backend Development, AI Integration, Frontend Integration |
| Team Member 2 | Frontend UI & Dashboard |
| Team Member 3 | Documentation & Presentation |

---

# 📌 Current Version

**Release:** v1.0

---

# 📄 License

This project was developed for academic and prototype purposes.

---

⭐ If you found this project useful, consider giving it a star on GitHub.
