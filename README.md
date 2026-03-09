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

## 📦 Installation & Setup
```bash
# Backend
pip install -r requirements.txt
python app.py

# Frontend
npm install
npm start
