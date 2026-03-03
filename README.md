# 🎓 Student Management System (Full-Stack)

A professional Full-Stack application developed to manage student records efficiently. This project demonstrates the integration of a **Django REST API** with a **React.js** frontend, secured by **JWT authentication**.

## 🚀 Key Features
* **Secure Authentication:** User login system implemented using **JSON Web Tokens (JWT)**.
* **Dynamic Dashboard:** View a real-time list of students fetched from the backend.
* **CRUD Operations:** Seamlessly **Add** and **Delete** student records.
* **Instant UI Updates:** Utilizes **React Hooks** to update the interface without page reloads.
* **API Integration:** Communication between frontend and backend via **Axios**.

## 🛠️ Tech Stack
* **Frontend:** React.js, Axios, CSS3
* **Backend:** Django, Django REST Framework (DRF)
* **Security:** SimpleJWT
* **Database:** SQLite (default)
* **Version Control:** Git & GitHub

## 🔧 Installation & Setup

### 1. Backend Setup (Django)
```bash
# Navigate to backend directory
cd backend

# Create and activate virtual environment
python -m venv venv
# On Windows: venv\Scripts\activate

# Install requirements (if you have a requirements.txt)
# pip install -r requirements.txt

# Run migrations and start server
python manage.py migrate
python manage.py runserver

# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start the development server
npm start