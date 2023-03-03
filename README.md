# todo-list
Django Todo List App with Class-Based Views
This is a Django-based web application for creating and managing a todo list. It allows users to create and delete tasks as well as mark tasks as completed.

Features
User Authentication: Users can sign up, log in, and log out. Users can only access their own tasks.
Task Management: Users can create new tasks, delete tasks, and mark tasks as complete.
User Profile: Users can view their own profile page and change their password.
Requirements
Python 3
Django 3.2
Setup
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/django-todo-app.git
Create a virtual environment:

bash
Copy code
python -m venv env
source env/bin/activate
Install the dependencies:

bash
Copy code
pip install -r requirements.txt
Run the migrations:

bash
Copy code
python manage.py migrate
Create a superuser:

bash
Copy code
python manage.py createsuperuser
Start the development server:

bash
Copy code
python manage.py runserver
Usage
Navigate to http://localhost:8000 in your web browser.
Register for an account or log in if you already have an account.
Create new tasks, delete tasks, and mark tasks as complete.
Notes
This app is built using Django's class-based views.
The app uses Django's built-in authentication system to handle user accounts.
User accounts are restricted so that users can only see and modify their own tasks.



