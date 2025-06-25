# Online Course Enrollment System

This project is a web-based application developed using Django that allows students to enroll in courses for their current semester. It was created as part of a college academic project to simulate a real-world course registration system used in universities.

## What this project does

The application provides a simple interface for:

* Students to register and log in
* Viewing available semester-specific courses
* Enrolling in selected courses
* Admin management of course listings and student enrollments

## Key Features

* Student authentication (login and registration)
* Course listing filtered by semester
* Enroll and drop functionality
* Admin panel for managing courses and users
* Error handling for invalid enrollments (like duplicate enrollments)

## Tech Stack

* **Backend:** Django (Python)
* **Frontend:** HTML, CSS (Bootstrap for styling)
* **Database:** SQLite (default Django DB)
* **Authentication:** Django's built-in auth system

## How to run the project locally

1. Clone the repo:

   ```
   git clone https://github.com/yourusername/online-course-enrollment.git
   ```

2. Navigate into the project folder:

   ```
   cd online-course-enrollment
   ```

3. Create a virtual environment:

   ```
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

4. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

5. Apply migrations:

   ```
   python manage.py makemigrations
   python manage.py migrate
   ```

6. Run the development server:

   ```
   python manage.py runserver
   ```

7. Access the app at `http://127.0.0.1:8000/`

## Admin Panel

To access the Django admin panel:

1. Create a superuser:

   ```
   python manage.py createsuperuser
   ```

2. Visit `http://127.0.0.1:8000/admin/` and log in with the admin credentials

## Why this project matters

This project helped understand how real-time applications like college ERP systems work—handling user sessions, managing data models, and building a clean user interface with Django. It can be extended further with features like payment integration, schedule conflict checks, or a waitlist system.

## Credits

Built by Gaja Sankar Raja as a semester project to practice full-stack development using Django.
