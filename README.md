# 🏥 Hospital Appointment Chatbot

An intelligent chatbot system that enables patients to book hospital appointments without human assistance.  
The system analyzes patient symptoms using AI, routes them to the appropriate medical department, and completes appointment booking automatically.

---


## 🚀 Features
- User registration and login with secure authentication
- Intelligent symptom analysis using OpenAI
- Automatic routing to the relevant medical department
- Real-time retrieval of available appointments
- Appointment booking via external scheduling API
- Full end-to-end chatbot experience

---

## System Architecture
React frontend sends requests to a Flask backend API.
The backend handles authentication, AI processing using OpenAI, and appointment booking through the GBooking external API.
All user data and sessions are stored in MongoDB.
---
User → React Frontend → Flask API → MongoDB
                     → OpenAI API
                     → GBooking API

---
## 🧠 System Flow
1. User registers and logs in
2. User describes symptoms in natural language
3. Message is sent to OpenAI for analysis
4. AI determines the relevant medical department
5. System retrieves available appointments from GBooking
6. User selects and books an appointment

---

## 🛠️ Tech Stack
### Backend
- Python (Flask)
- MongoDB
- OpenAI API
- REST APIs

### Frontend
- React

### External Services
- GBooking API (appointment scheduling)

---
## 🔗 Repositories

- [Frontend Repository](https://github.com/SaeedYasen/TsofenFrontend)
- [Backend Repository](https://github.com/SaeedYasen/TsofenBackend)
  
---

## 👨‍💻 My Role
- Implemented user registration and authentication logic
- Managed database interactions with MongoDB
- Built chatbot conversation flow and backend logic
- Integrated OpenAI API for symptom analysis
- Connected scheduling system (GBooking API) to fetch and book appointments

---

## screenshots
SignUpForm
<img width="275" height="561" alt="Screenshot 2026-03-09 172634" src="https://github.com/user-attachments/assets/15500ba5-3404-4ce5-80b9-cbf4482cb514" />

LoginForm 
<img width="444" height="388" alt="Screenshot 2026-03-09 172657" src="https://github.com/user-attachments/assets/b76c307c-5612-4e7c-bfe5-9f52db86fd6c" />

Select appointment 
<img width="1277" height="606" alt="Screenshot 2026-03-09 172751" src="https://github.com/user-attachments/assets/ac137fd9-0ce5-4971-b369-100e72924b8a" />
## 📦 Installation & Setup
```bash
# Backend
pip install -r requirements.txt
python app.py

# Frontend
npm install
npm start
