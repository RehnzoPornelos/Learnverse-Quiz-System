# 🚀 Learnverse Quiz System

[![Status](https://img.shields.io/badge/status-active-brightgreen.svg)]()
[![Made With](https://img.shields.io/badge/made%20with-💡%20AI-orange.svg)]()

**Learnverse** is a web-based quiz platform that enables professors to automatically generate quizzes from e-learning materials, administer assessments to students, and analyze performance through actionable insights and recommendations.


---


## ✨ Features

The system's main functions includes:
* automatic quiz creation through e-learning material (supports question types such as Multiple Choice, True/False, Identification, Short Answer and Essay)
* student performance analytics for each sections that the professor handles with detailed insights
* provides recommendations of what to do based on the results of student progress
* quiz taking can automatically detect tabs or window leaving, preventing cheating


---


## VIDEO DEMONSTRATION

### 1. Quiz Creation
![Quiz Creation Demo](img/QuizCreation.gif)

### 2. Quiz Taking
![Quiz Taking Demo](img/QuizTaking.gif)

See fully-voiced demonstration here -> https://youtu.be/yRveX1HP7CI


---


## 🎯 Project Highlights

- Full-stack web application built with React, FastAPI, and PostgreSQL
- AI-powered quiz generation from uploaded learning materials
- Supports PDF, Word, and PowerPoint document processing
- Real-time quiz monitoring using Socket.IO
- Automated student performance analytics and recommendations
- Anti-cheating detection through tab and window focus monitoring
- Role-based authentication for professors and students


---


## 🛠️ Technology Stack

### Frontend
- React
- TypeScript
- Vite
- Tailwind CSS
- Shadcn/UI
- React Router
- TanStack Query
- Recharts & Plotly.js
- Socket.IO

### Backend
- FastAPI
- Python
- Socket.IO
- Uvicorn

### Database & Cloud Services
- PostgreSQL
- Supabase
  - Authentication
  - Storage
  - Realtime API
  - Edge Functions

### AI & Document Processing
- Groq API
- Llama Models
- DeepSeek-R1
- PyMuPDF
- python-docx
- python-pptx

### Development Tools
- Git & GitHub
- ESLint
- npm
- Bun


---


## 🏗️ System Architecture

Frontend (React + TypeScript)
        │
        ▼
Backend API (FastAPI)
        │
        ├── Groq API
        │      └── AI Quiz Generation
        │
        └── Supabase
               ├── PostgreSQL Database
               ├── Authentication
               ├── Storage
               └── Realtime Services
               

---


## 🚀 How to run


1. Download Learnverse as a ZIP file
2. Extract the folder from the ZIP
3. Open and get the environment variables here for testing: https://drive.google.com/drive/folders/1HtYN0sMNAVL0_JfLtRQ_vvpTpf9QAf6K?usp=drive_link
4. Paste the environment variables respectively inside '.env' from the backend folder and '.env.local' on the Learnverse's root folder.
5. Run the QuizLauncher.bat
6. Start the system


---


## 📄 License

This project was developed for academic and educational purposes.

Copyright © 2025
Pornelos, Rehnzo P. & Valerio, Mark Francis
Universidad de Manila

**Copyright © [2025] [Pornelos, Rehnzo P. | Valerio, Mark Francis @ Universidad de Manila]. All rights reserved.**