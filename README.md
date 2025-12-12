**👤 Author**
Isaac Akhtar Zada

**📘 Django Blog App**

A simple, beginner-friendly blog application built with Python, Django, and SQLite.
This project demonstrates Django fundamentals such as models, views, templates, URL routing, and the admin panel.

**🚀 Features**

📝 Create and manage blog posts through Django Admin

📄 Homepage that lists all posts

🔍 Individual post detail pages

🎨 Clean and simple HTML templates

🗂 Organized Django project structure

🛠 Fully local development environment with virtual environment support

🛠 Technologies Used

Python 3.11

Django 5.x

SQLite3

HTML5 / Django Template Language

pip / venv

**📂 Project Structure**
blog-app/
│
├── blog/                  # Blog app (models, views, admin, urls)
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── admin.py
│
├── django_project/        # Main Django project settings
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── templates/             # HTML templates
│   ├── home.html
│   └── post_detail.html
│
├── manage.py              # Django management script
├── db.sqlite3             # Local SQLite database
└── .venv/                 # Virtual environment (ignored)

**▶️ How to Run the Project**
1. Clone the repository
git clone https://github.com/IsaacAkh/blog-app.git
cd blog-app

2. Create and activate a virtual environment
python3 -m venv .venv
source .venv/bin/activate  # Mac/Linux

3. Install dependencies
pip install -r requirements.txt


(If requirements.txt doesn’t exist, run pip freeze > requirements.txt after install.)

4. Apply migrations
python manage.py migrate

5. Create a superuser
python manage.py createsuperuser

6. Run the server
python manage.py runserver


**Visit the app at:**

👉 http://127.0.0.1:8000/

👉 Admin panel: http://127.0.0.1:8000/admin/

✏️ Creating Blog Posts

Log in to the admin panel /admin/

Select Posts

Add a title, author, and body text

Save and the post will appear on the homepage


**📄 License**

This project is for educational purposes and free to use.

