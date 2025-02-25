Project Management App

This is a simple project management web application built with Django. It allows users to create, update, and delete projects and tasks within those projects. The app features authentication, role-based access, and a user-friendly interface using HTML, CSS, and Bootstrap.

Features

User authentication (login/logout)

Create, edit, and delete projects

Add and manage tasks within projects

Responsive UI with Bootstrap

Uses Django's built-in SQLite database

Technologies Used

Backend: Django (Python)

Database: SQLite 

Frontend: HTML, CSS, Bootstrap

Installation

Clone the repository:

git clone   https://github.com/Pepi134/XGateTask.git


cd crud_project

Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Apply migrations:

python manage.py migrate

Create a superuser (optional, for admin access):

python manage.py createsuperuser

Run the development server:

python manage.py runserver

Open the app in your browser at http://127.0.0.1:8000/

Usage

Register or log in as a user.

Create projects and add tasks within them.

Edit or delete projects and tasks as needed.

Use the admin panel (/admin) for advanced management (if superuser access is created).
