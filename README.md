# AI Voice-Based Hospital Appointment Booking System

## 🚀 Overview
This project is an AI-powered voice receptionist that automates hospital appointment booking using Generative AI and real-time speech interaction.

## 🛠 Tech Stack
- Python
- FastAPI
- Google Gemini API
- SQLite
- gTTS (Text-to-Speech)
- Tailwind CSS
- JavaScript Speech Recognition API

## ✨ Features
- Multilingual Support (English, Hindi, Telugu)
- Voice-based conversation
- Doctor listing
- Slot availability checking
- Appointment booking
- Real-time speech response

## 📂 Project Structure
- app.py → Backend logic (FastAPI + AI integration)
- frontend.html → Voice call UI
- SQLite database → Appointment management

## 🔥 How to Run

1. Install dependencies:
pip install fastapi uvicorn gtts google-generativeai python-dotenv

2. Add Gemini API key in .env file:
GEMINI_API_KEY=your_api_key_here

3. Run server:
python app.py

4. Open in browser:
http://127.0.0.1:8000

