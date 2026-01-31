# 📝 Django TODO App

A simple and clean **Django-based TODO application** that allows users to create, update, mark, and delete tasks.  
This project demonstrates **CRUD operations**, **Django ORM**, **template inheritance**, and **Bootstrap styling**.

---

## 🚀 Features

- ➕ Add new tasks
- ✏️ Edit existing tasks
- ✅ Mark tasks as completed / incomplete
- 🗑️ Delete tasks with confirmation
- 📅 Auto timestamp for task creation
- 🔐 Secure operations using CSRF protection
- 🎨 Responsive UI using Bootstrap 5
- 🛠 Admin panel with search & filters

---

## 🧰 Tech Stack

- **Backend:** Python, Django  
- **Frontend:** HTML, Bootstrap 5  
- **Database:** SQLite3  
- **Version Control:** Git & GitHub  

---

## 📂 Project Structure

todoproject/
│
├── todo/
│ ├── migrations/
│ ├── templates/
│ │ └── todo/
│ │ ├── base.html
│ │ ├── task_list.html
│ │ ├── task_form.html
│ │ └── task_confirm_delete.html
│ ├── models.py
│ ├── views.py
│ ├── urls.py
│ └── admin.py
│
├── todoproject/
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
│
├── manage.py
├── db.sqlite3
└── README.md



---

## ⚙️ Installation & Setup (Local)

1️⃣ Clone the repository
git clone https://github.com/your-username/django-todo-app.git
cd django-todo-app

2️⃣ Create virtual environment
python -m venv env
source env/bin/activate   # On Windows: env\Scripts\activate

3️⃣ Install dependencies
pip install django

4️⃣ Apply migrations
python manage.py migrate

5️⃣ Create superuser (optional)
python manage.py createsuperuser

6️⃣ Run the server
python manage.py runserver

Open in browser:
👉 http://127.0.0.1:8000/

🔑 Admin Panel
Access admin dashboard:
👉 http://127.0.0.1:8000/admin/

## Admin features:
- View all tasks
- Filter by completed status
- Search by title and description
- Sort by creation date

🌍 Deployment
This project can be deployed on:
- PythonAnywhere
- Render
- Railway
- AWS EC2

Deployed using GitHub + PythonAnywhere.

📌 Resume Description
Built and deployed a Django-based TODO application implementing CRUD operations, Django ORM, admin customization, Bootstrap UI, and Git-based version control.

🧠 What I Learned
-- Django MTV architecture
-- Django ORM & migrations
-- Template inheritance
-- CSRF protection
-- Git & GitHub workflow
-- Deployment basics

# 🔮 Future Improvements
-- User authentication (login/register)
-- Tasks per user
-- Pagination
-- Task priority
-- REST API using Django REST Framework

👨‍💻 Author
Pavan Devidas Jadhav

GitHub: https://github.com/jpavan05

LinkedIn: https://www.linkedin.com/in/pavan-jadhav-72620a287/

