# 🚀 SmartCampus Hub  
### 🏫 Digital Campus Issue Reporting & Management System

SmartCampus Hub is a web-based application that enables students to report campus infrastructure issues digitally while allowing administrators to track and resolve them efficiently.  
The system improves **transparency**, **accountability**, and **communication** between students and campus authorities.

---

## 🌐 Live Demo
👉 https://smart-campus-issue-repor-8a6ea.web.app

---

## 📌 Problem Statement
In many college campuses, infrastructure and maintenance issues such as broken classroom equipment, electrical faults, damaged furniture, cleanliness problems, or internet issues are reported informally.  
This leads to delayed resolutions, lack of accountability, and poor communication.

A centralized, transparent, and easy-to-use digital system is required to manage and resolve campus issues efficiently.

---

## 💡 Solution Overview
SmartCampus Hub provides a centralized platform where:

- **Students** can log in and report campus issues with details.
- **Administrators** can view all reported issues and update their status.
- **Real-time updates** ensure transparency and faster issue resolution using Firebase.

---

## ✨ Key Features

### 👨‍🎓 Student Features
- Secure login and registration
- Submit campus issues with title and description
- Optional image URL support
- Track issue status in real time

### 🧑‍💼 Admin Features
- Admin-only dashboard
- View all reported issues
- Update issue status:
  - Pending  
  - In Progress  
  - Resolved
- Role-based access control

---

## 🔐 Security & Access
- Firebase Authentication (Email & Password)
- Role-based access (Student / Admin)
- Firestore security rules for controlled data access

---

## 🛠️ Technology Stack

### Frontend
- HTML5  
- CSS3  
- JavaScript (ES6)

### Backend & Cloud Services
- Firebase Authentication  
- Firestore Database  
- Firebase Hosting  

---

## 🏗️ System Architecture

User (Student / Admin)
       ↓
Web Application (HTML, CSS, JS)
       ↓
Firebase Authentication
       ↓
Firestore Database (Real-time)
       ↓
Admin Dashboard (Status Management)

---

## 🚀 Getting Started (Local Setup)

### Prerequisites
- Modern web browser
- Firebase project

### Steps
## 🚀 Getting Started (Local Setup)

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Shivamshekharss/SmartCampus-Hub.git
cd SmartCampus-Hub

2. Configure Firebase

Create a project in Firebase Console

Enable:

Authentication (Email/Password)

Firestore Database

Copy your Firebase configuration and paste it into app.js

3.Run the project locally

npx serve .
# OR
python -m http.server 8000

4. Open in browser
http://localhost:8000

---

## ▶️ Start Using the App

- Register or log in as a **student** to submit campus issues  
- Log in as an **admin** to manage and resolve reported issues  

---
 ```

## 🌍 Real-World Impact

- Faster resolution of campus issues  
- Improved transparency between students and administrators  
- Better campus infrastructure management  
- Data-driven maintenance planning  

## 🔮 Future Enhancements

- Google Maps integration for issue location
-  AI-based issue categorization
- Mobile application version
-Analytics dashboard for administrators
-Priority-based issue handling

## 📄 License

This project is developed as a student innovation project and is free to use for learning and academic purposes.

## 👨‍💻 Authors

Shivam Shekhar & Anushka
Built with ❤️ using HTML, CSS, JavaScript & Google Firebase
