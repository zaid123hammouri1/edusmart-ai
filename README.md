# EduSmart AI

EduSmart AI is an AI-powered educational platform that combines a React frontend, a FastAPI backend, machine learning prediction models, and chatbot features to support students, lecturers, and administrators in an academic environment.

## Overview

The system is designed to provide a centralized educational platform with role-based functionality for:

- Students
- Lecturers
- Administrators

It includes course management, student-related services, educational materials, quiz and assessment features, chatbot interaction, and machine learning-based prediction components.

## Key Features

### Student Features

- Student dashboard
- Course viewing and course details
- Attendance tracking
- Course materials access
- Quiz participation
- Quiz result viewing
- Profile management
- Chatbot support

### Lecturer Features

- Lecturer dashboard
- Course management
- Student lists
- Attendance management
- Assignment management
- Quiz creation and management
- Quiz results review
- Course materials upload and management
- Lecturer profile page

### Admin Features

- Admin dashboard
- Student management
- Lecturer management
- Department management
- Course management
- Semester management
- Course enrollment management
- Student detail pages
- Role-based administration

### AI and Machine Learning Features

- Student performance prediction
- Educational data analysis
- Trained machine learning models
- Chatbot support for academic interaction
- Model artifacts stored for backend prediction usage

## Tech Stack

### Frontend

- React
- JavaScript
- Tailwind CSS
- Axios
- React Router

### Backend

- FastAPI
- Python
- SQLite
- Pydantic
- REST API architecture

### Machine Learning

- scikit-learn
- joblib
- Trained ML models
- Educational datasets
- Prediction pipeline integration

## Project Structure

```text
edusmart-ai/
├── backend/
│   ├── routes/
│   ├── utils/
│   ├── main.py
│   ├── models.py
│   ├── schemas.py
│   ├── database.py
│   ├── auth.py
│   ├── config.py
│   ├── seed_data.py
│   └── requirements.txt
│
├── edusmartai-frontend/
│   ├── public/
│   ├── src/
│   │   ├── api/
│   │   ├── components/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── pages/
│   │   ├── routing/
│   │   └── utils/
│   ├── package.json
│   └── tailwind.config.js
│
├── Saved_Models/
│   ├── axi_rf_model.joblib
│   ├── axi_scaler.joblib
│   ├── oulad_model_fixed.joblib
│   └── oulad_scaler_fixed.joblib
│
├── AXI_Training/
│   └── model training notebook
│
├── .gitignore
└── README.md