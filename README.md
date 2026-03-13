# 🏥 Hospital Appointment Chatbot

An AI-powered chatbot system that allows patients to book hospital appointments automatically without human assistance.

The system analyses patient symptoms using AI, identifies the appropriate medical department, retrieves available appointments from an external scheduling system, and allows the user to book a doctor directly.

---

# 🚀 Features

- Secure user registration and login
- AI-based symptom analysis using OpenAI
- Automatic routing to the relevant medical department
- Retrieval of available appointments from the external system
- Appointment booking through the scheduling API
- End-to-end chatbot booking experience

---

# 🧠 System Architecture

The system follows a typical **Frontend → Backend → External Services** architecture.

The React frontend sends requests to a Flask backend API.  
The backend handles authentication, AI processing using OpenAI, and appointment booking through the GBooking external API.  
User data and sessions are stored in MongoDB.


User → React Frontend → Flask Backend API → MongoDB
→ OpenAI API
→ GBooking API


---

# 🔄 System Flow

1. User registers and logs in
2. User describes symptoms in natural language
3. Message is sent to OpenAI for analysis
4. AI determines the appropriate medical department
5. Backend retrieves available appointments from the GBooking API
6. User selects a doctor and appointment slot
7. Appointment is booked and stored in the database

---

# 🛠️ Tech Stack

## Backend
- Python
- Flask
- MongoDB
- REST APIs
- OpenAI API

## Frontend
- React

## External Services
- GBooking API (appointment scheduling)

---

# 👨‍💻 My Role

- Implemented secure user authentication
- Built backend logic for chatbot flow
- Integrated OpenAI API for symptom analysis
- Connected external booking system (GBooking API)
- Managed database operations using MongoDB
- Implemented API endpoints for appointment retrieval and booking

---

# 📸 Screenshots

### Sign Up
<img width="275" height="561" src="https://github.com/user-attachments/assets/15500ba5-3404-4ce5-80b9-cbf4482cb514" />

### Login
<img width="444" height="388" src="https://github.com/user-attachments/assets/b76c307c-5612-4e7c-bfe5-9f52db86fd6c" />

### Select Appointment
<img width="1277" height="606" src="https://github.com/user-attachments/assets/ac137fd9-0ce5-4971-b369-100e72924b8a" />

---

# 🔗 Repositories

Frontend:  
https://github.com/SaeedYasen/TsofenFrontend

Backend:  
https://github.com/SaeedYasen/TsofenBackend

---

# ⚙️ Installation

### Backend

```bash
pip install -r requirements.txt
python app.py
Frontend
npm install
npm start
