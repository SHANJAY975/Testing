# 🗂️ Team Task Manager (Full Stack Web App)

A full-stack web application built using **Flask + SQLite + HTML/CSS/JS** that allows teams to manage projects, assign tasks, and track progress with role-based access (Admin & Member).

---

## 📌 Features

### 🔐 Authentication
- User Login (Admin / Member)
- Session-based access control

### 👨‍💼 Admin Panel
- Dashboard with overview stats
- Create / Edit / Delete Projects
- Add / Manage Members
- Create / Assign / Update Tasks
- Track task status (Pending / In Progress / Completed)

### 👨‍💻 Member Panel
- View assigned tasks
- Update task status
- Simple dashboard view

### 📊 Task Management
- Task assignment to members
- Status tracking
- Real-time updates in admin panel

---

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Bootstrap (optional)
- **Backend:** Python Flask
- **Database:** SQLite
- **Authentication:** Session-based login system

---

## 📁 Project Structure
team-task-manager/
│
├── app.py
├── requirements.txt
├── team_task_manager.db
│
├── templates/
│ ├── login.html
│ ├── admin/
│ └── member/
│
├── static/
│ ├── css/
│ ├── js/
│
└── README.md

---

## ⚙️ Setup Instructions

### 1️⃣ Install dependencies
```bash
pip install flask

admin login id
    Email: admin@gmail.com
    Password: 1234