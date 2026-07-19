# Event Registration System

A full-stack Event Registration System built using **Django REST Framework**, **React (Vite)**, and **PostgreSQL**. This application allows users to view events, register for events, and manage registrations through a secure authentication system.

## 🚀 Features

- User Authentication (JWT)
- View Available Events
- Register for Events
- Cancel Event Registration
- Admin Panel for Event Management
- REST API with Django REST Framework
- PostgreSQL Database Integration
- React Frontend with Vite
- CORS Enabled for Frontend-Backend Communication

## 🛠️ Technologies Used

### Backend
- Python
- Django
- Django REST Framework
- PostgreSQL
- JWT Authentication
- django-cors-headers
- Pillow

### Frontend
- React
- Vite
- JavaScript
- CSS

## 📂 Project Structure

```
EventRegister/
│── events/
│── event_register_pro/
│── manage.py

frontend/
│── src/
│── public/
│── package.json
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/Event-Registration-System.git
```

### Backend Setup

```bash
cd EventRegister

pip install -r requirements.txt

python manage.py migrate

python manage.py runserver
```

### Frontend Setup

```bash
cd frontend

npm install

npm run dev
```

## Database

- PostgreSQL

Update the `.env` file:

```env
DB_NAME=event_db
DB_USER=postgres
DB_PASSWORD=your_password
DB_HOST=localhost
DB_PORT=5432
```

## API Endpoints

- `/api/events/`
- `/api/register/`
- `/api/my-registrations/`
- `/api/token/`
- `/api/token/refresh/`

## Screenshots

- Login Page
- Events Page
- Admin Panel

(Add screenshots here if available.)

## Author

**Vivek Bhand**

GitHub: https://github.com/202301070201-droid
