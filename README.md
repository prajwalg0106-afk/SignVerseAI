# 🤟 SignVerseAI — Indian Sign Language Learning Platform

SignVerseAI is an accessibility-focused learning platform designed to help people learn Indian Sign Language (ISL) through interactive lessons, vocabulary practice, quizzes, progress tracking, and camera-based hand tracking.

The goal is to make sign-language learning more engaging and accessible for students, beginners, and anyone interested in inclusive communication.

## ✨ Features

- 📚 Interactive learning dashboard
- 🤟 Indian Sign Language learning modules
- 🔎 Sign vocabulary library
- 📝 Interactive quizzes and practice
- 📷 Webcam-based hand tracking prototype
- 🤖 Animated learning assistant prototype
- 🔐 User registration and login
- 📊 Learning progress tracking
- 💾 Backend persistence using SQLite

## 🛠️ Tech Stack

**Frontend:** React, Vite, JavaScript, CSS

**Backend:** Python, FastAPI

**Database:** SQLite

**Computer Vision:** MediaPipe hand tracking

## 🚀 Getting Started

### Prerequisites

- Python 3
- Node.js and npm
- A modern web browser

### Backend Setup

Create and activate a virtual environment from the project root:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r backend\requirements-signverse.txt
cd backend
python -m uvicorn signverse_api:app --reload
```

API documentation: http://127.0.0.1:8000/docs

### Frontend Setup

Open a second terminal in the project root:

```powershell
cd frontend
npm install
npm run dev
```

Open the local URL shown in the terminal.

## 🇮🇳 ISL Learning Resources

Indian Sign Language Research and Training Centre (ISLRTC):

https://divyangjan.depwd.gov.in/islrtc/

## 🔮 Future Improvements

- Verified ISL demonstration videos
- Trained ISL sign-recognition model
- Sign accuracy feedback and guided practice
- Accurate animated signing avatar
- Expanded lessons and vocabulary
- Improved learner analytics and accessibility testing

## ⚠️ Development Status

SignVerseAI is under development. Camera-based hand tracking does not itself recognize ISL signs. A trained and validated sign-recognition model and educator-reviewed demonstrations remain future development goals.

## 👨‍💻 Author

Developed as a software project exploring accessibility, Indian Sign Language education, and AI-assisted learning.

---

⭐ Contributions and feedback are welcome!
