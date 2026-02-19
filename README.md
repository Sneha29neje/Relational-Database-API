# 🍹 Hotel Web - Django REST API Project

## 📌 Project Description
Hotel Web is a Django-based REST API project that manages drink items for a hotel system.  
This project uses **Django** and **Django REST Framework** to create API endpoints for managing drinks.

The project includes:
- Django project: `Hotel_web`
- Django app: `drinks`
- SQLite database (default)
- REST API with serializers

---

## 🏗️ Project Structure

```
RAPIRD/
│
├── Hotel_web/
│   ├── manage.py
│   ├── db.sqlite3
│   │
│   ├── Hotel_web/
│   │   ├── settings.py
│   │   ├── urls.py
│   │   ├── asgi.py
│   │   └── wsgi.py
│   │
│   └── drinks/
│       ├── models.py
│       ├── views.py
│       ├── serializers.py
│       ├── admin.py
│       ├── apps.py
│       └── migrations/
│
└── rd/   (Virtual Environment - optional)
```

---

## ⚙️ Technologies Used

- Python 3.x
- Django
- Django REST Framework
- SQLite Database

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

### 2️⃣ Create Virtual Environment (Recommended)

```bash
python -m venv venv
```

Activate virtual environment:

**Windows**
```bash
venv\Scripts\activate
```

**Mac/Linux**
```bash
source venv/bin/activate
```

### 3️⃣ Install Dependencies

```bash
pip install django
pip install djangorestframework
```

(Or if requirements.txt exists)

```bash
pip install -r requirements.txt
```

---

## 🛠️ Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

---

## ▶️ Run the Development Server

```bash
python manage.py runserver
```

Server will start at:
```
http://127.0.0.1:8000/
```

---

## 📡 API Endpoints

Example endpoints (based on drinks app):

```
GET     /drinks/
POST    /drinks/
GET     /drinks/<id>/
PUT     /drinks/<id>/
DELETE  /drinks/<id>/
```

You can test APIs using:
- Browser
- Postman
- Thunder Client
- cURL

---

## 🗃️ Database

- Default database: SQLite (`db.sqlite3`)
- Can be changed in `settings.py`

---

## 🔐 Admin Panel

Create superuser:

```bash
python manage.py createsuperuser
```

Login at:

```
http://127.0.0.1:8000/admin/
```

---

## 📌 Features

✔ Create drink items  
✔ Retrieve drink list  
✔ Update drink details  
✔ Delete drinks  
✔ REST API using serializers  

---

## 📜 License

This project is for educational purposes.

---

## 👨‍💻 Author

Developed by: Your Name  
Project Type: Django REST API Practice Project

---

⭐ If you like this project, give it a star on GitHub!
