# Team Manager

A full-stack web application built using Django that helps teams manage projects, assign tasks, and track work progress with role-based access control.

## 🚀 Features

* User Authentication (Signup/Login/Logout)
* Role-Based Access (Admin & Members)
* Create and Manage Projects
* Assign Tasks to Team Members
* Task Status Tracking
* Dashboard for Project Monitoring
* Overdue Task Tracking
* Responsive UI using HTML & CSS
* Django Admin Panel
* Secure Backend with CSRF Protection
* Database Integration with SQLite/MySQL

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* JavaScript

### Backend

* Python
* Django

### Database

* SQLite (Default Django DB)

### Deployment

* Railway
* Gunicorn
* Whitenoise

---

## 📂 Project Structure

```bash
teammanager/
│
├── accounts/              # Authentication app
├── projects/              # Project & task management
├── static/                # CSS, JS, Images
├── templates/             # HTML Templates
├── media/                 # Uploaded files
├── teammanager/           # Main Django settings
├── manage.py
├── requirements.txt
└── README.md
```

---

## 🔐 Authentication System

The application provides:

* User Registration
* User Login
* Logout Functionality
* Session Handling
* Access Restrictions for Unauthorized Users

---

## 📋 Task Management

Users can:

* Create Projects
* Add Tasks
* Assign Tasks to Members
* Update Task Status
* View Pending/Completed Tasks
* Track Deadlines

Task statuses include:

* Pending
* In Progress
* Completed

---

## 👥 Roles

### Admin

* Manage projects
* Assign tasks
* Monitor all team activity

### Member

* View assigned tasks
* Update task progress
* Manage personal work

---

## 📊 Dashboard

The dashboard displays:

* Total Projects
* Total Tasks
* Completed Tasks
* Pending Tasks
* Overdue Tasks

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Vishnureddy630/teammanager.git
cd teammanager
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### 3️⃣ Activate Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux/Mac

```bash
source venv/bin/activate
```

### 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 5️⃣ Run Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 6️⃣ Create Superuser

```bash
python manage.py createsuperuser
```

### 7️⃣ Run Server

```bash
python manage.py runserver
```

---

## 🌐 URLs

| Page        | URL           |
| ----------- | ------------- |
| Signup      | `/signup/`    |
| Login       | `/login/`     |
| Dashboard   | `/dashboard/` |
| Projects    | `/projects/`  |
| Tasks       | `/tasks/`     |
| Admin Panel | `/admin/`     |

---

## ☁️ Deployment

This project can be deployed using:

* Railway
* Render
* PythonAnywhere
* VPS Hosting

### Production Tools

* Gunicorn
* Whitenoise
* PostgreSQL (Recommended)

---

## 📌 Future Improvements

* Email Notifications
* Team Chat System
* File Uploads
* REST API Integration
* JWT Authentication
* Activity Logs
* Calendar Integration
* Charts & Analytics

---

## 🧑‍💻 Author

* GitHub: [Vishnureddy630/teammanager Repository](https://kandi.openweaver.com/ruby/StuyPulse/teammanager?utm_source=chatgpt.com)

---

## 📄 License

This project is developed for learning and portfolio purposes.
