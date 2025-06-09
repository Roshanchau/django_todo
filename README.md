
# 📝 Django To-Do App

A simple and clean To-Do list web application built using Django. This project allows users to add, view, and delete tasks efficiently using Django’s MVT design pattern and Bootstrap styling.

---

## 🚀 Features

- ✅ Add tasks with a simple form
- 📋 View all tasks (sorted by newest first)
- ❌ Delete tasks from the list
- 🧼 Minimal and responsive UI using Bootstrap
- 🗃️ Uses Django's default SQLite database

---

## 🛠️ Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS (Bootstrap)
- **Database:** SQLite (default Django database)

---

## 📦 Getting Started

### 🔧 Requirements

- Python 3.x
- pip (Python package manager)
- Git (optional)

### 🖥️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/Roshanchau/django_todo.git
cd django_todo
```

2. **Create and activate virtual environment**

```bash
python -m venv env
env\Scripts\activate  # On Windows
# source env/bin/activate  # On macOS/Linux
```

3. **Install Django**

```bash
pip install django
```

4. **Run migrations**

```bash
python manage.py makemigrations
python manage.py migrate
```

5. **Start the development server**

```bash
python manage.py runserver
```

6. **Access the app**

Open your browser and go to [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🧪 Admin Panel

To access the Django admin panel:

1. Create a superuser:

```bash
python manage.py createsuperuser
```

2. Visit [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/) and log in.

---

## 📁 Project Structure

```
django_todo/
│
├── todo/               # Main app
│   ├── migrations/
│   ├── templates/
│   │   └── todo/
│   │       └── index.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── todo_site/          # Django project settings
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── db.sqlite3
├── manage.py
└── README.md
```

---

## 🙋‍♂️ Author

**Roshan Chaudhary**  
📎 [GitHub Profile](https://github.com/Roshanchau)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📌 Acknowledgment

Based on the tutorial from [GeeksforGeeks - Python To-Do Web App using Django](https://www.geeksforgeeks.org/python-todo-webapp-using-django/)
