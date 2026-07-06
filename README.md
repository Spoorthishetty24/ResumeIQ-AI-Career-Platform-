# 📄 ResumeIQ v3 — Full-Stack AI Career Platform

## 🗺️ 10 Complete Features / Pages

| # | Page | Description |
|---|------|-------------|
| 1 | 🏠 Landing Page | Hero, stats (10K+ resumes), features, testimonials, CTA |
| 2 | 🔐 Auth | Login / Sign Up with role selection (Job Seeker / Recruiter) |
| 3 | 📊 Dashboard | Stats, scores, feature cards, latest analysis |
| 4 | 🔍 Resume Analyzer | ATS score, skill extraction, 5 improvements, keywords |
| 5 | 📈 Visual Insights | Pie chart, bar chart, radar chart for skill analytics |
| 6 | 🎯 Job Matching | 8 job roles, match %, skill gap, learning topics |
| 7 | 🌟 Career AI | Top 3 role recommendations with salary and match % |
| 8 | 🗺️ Roadmap | 30/60/90 day plans with weekly tasks, projects, courses |
| 9 | 🎤 Mock Interview | 5 questions, type answers, get AI feedback + scores |
| 10 | ✏️ Resume Builder | Section editor + AI enhancement per section |
| 11 | 📝 Cover Letter | 5 tones, generate, copy, regenerate |
| 12 | 📋 History | Last 10 analyses with charts |
| 13 | 👤 Profile | Photo upload, bio, edit details, save multiple resumes |
| 14 | 👨‍💼 Recruiter | Browse candidates, filter by skill, sort by ATS score |
| 15 | 🛠️ Admin | Analytics, job role CRUD, skill gap chart, user list |

## 🔑 Pre-built Test Accounts
- **Admin:**     admin@resumeiq.com     / admin123
- **Recruiter:** recruiter@resumeiq.com / recruiter123

## ⚙️ Setup

### 1. Add API Key — open `backend/.env`:
```
ANTHROPIC_API_KEY=sk-ant-YOUR_KEY_HERE
```
Get your free key at: https://console.anthropic.com

### 2. Run Backend:
```bash
cd backend
npm install
npm run dev
```

### 3. Run Frontend (new terminal):
```bash
cd frontend
npm install
npm start
```

Open: **http://localhost:3000**

## 🏗️ Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | React 18, Recharts, Bootstrap 5 |
| Backend | Express.js, Node.js |
| AI Engine | Anthropic Claude Sonnet 4 |
| Charts | Recharts (Pie, Bar, Radar) |
| File Upload | Multer |
| File Parsing | PDF.js, Mammoth.js (CDN) |
