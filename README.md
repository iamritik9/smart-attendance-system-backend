# Smart Attendance System - Backend

This is the backend service for the **Smart Attendance System using Face Recognition**, a full-stack web application developed as a college domain project. It enables modern, secure, and efficient attendance tracking through face recognition.

## 🔗 Frontend Repository

👉 [Smart Attendance System - Frontend](https://github.com/iamritik9/smart-attendance-system-frontend)

---

## 📌 Features

- REST APIs built with **Spring Boot (Java)**
- Integration with **Python-based face recognition**
- Role-based login: **Student**, **Staff**, and **Admin**
- Facial attendance marking with real-time timestamp
- Attendance and user data stored in **MySQL database**
- Admin dashboard:
  - Manage users (students/staff)
  - Add new users
  - View attendance logs
  - Generate timetables

---

## 🧠 Tech Stack

| Category        | Tech                  |
|----------------|-----------------------|
| Backend         | Spring Boot, Java     |
| Face Recognition | Python + OpenCV      |
| Database        | MySQL                 |
| Authentication | Gmail & Password login |
| API Testing     | Postman               |

---

## 🗂️ API Overview

Sample routes:

| Endpoint | Method | Description |
|---------|--------|-------------|
| `/api/login` | POST | Login with Gmail/password |
| `/api/student/attendance` | GET | Get student attendance |
| `/api/attendance/mark` | POST | Mark attendance with face |
| `/api/admin/create-user` | POST | Add student or staff |
| `/api/admin/view-attendance` | GET | View all attendance logs |

> 💡 Note: Face photos are currently uploaded manually using Postman.

---

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/smart-attendance-system-backend.git
   cd smart-attendance-system-backend
