# student-management-system

## Project Overview

The Student Management System is a web-based application developed using Django to simplify the management of student information. It provides a structured interface for adding, viewing, updating, and deleting student records.

The project demonstrates the use of Django for developing a database-driven web application with a simple and user-friendly interface.

## Features

* View student records in an organized list
* Add new student information
* Edit existing student details
* Delete student records
* Store student information using a database
* Simple and easy-to-use web interface
* Django-based backend for managing application logic

## Technologies Used

* **Python**
* **Django**
* **HTML**
* **CSS**
* **SQLite Database**

## Project Structure

```text
student_management_system/
│
├── manage.py
├── db.sqlite3
├── student_management_system/
│   ├── settings.py
│   ├── urls.py
│   └── ...
│
└── students/
    ├── models.py
    ├── views.py
    ├── urls.py
    └── ...
```

## How to Run the Project

1. Download or clone this repository.
2. Open the project folder in a terminal.
3. Make sure Python is installed.
4. Install Django if required:

```bash
pip install django
```

5. Start the Django development server:

```bash
python manage.py runserver
```

6. Open the following address in a web browser:

```text
http://127.0.0.1:8000/
```

## Database

The application uses SQLite to store student information. The database is managed through Django's built-in ORM and model system.

## Project Purpose

This project was developed as an academic activity to gain practical experience in Django web development, database management, CRUD operations, and basic web application design.

## Author

**Kavin P A**

B.E. Computer and Communication Engineering (CCE)

V. S. B. Engineering College

## Note

This project is intended for academic and learning purposes. It demonstrates the fundamental concepts required to develop and manage a database-driven web application using Django.
