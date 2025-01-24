# Task Manager

![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)

Task Manager is a simple and intuitive web application built with **Django** and **Bootstrap**. It allows users to manage their tasks efficiently by creating, updating, and deleting tasks. Users can also categorize tasks and track their status.

## Features

- **User Authentication**: Register, log in, and log out.
- **Task Management**: Create, update, and delete tasks.
- **Categories**: Organize tasks into categories (e.g., Work, Personal, Shopping).
- **Status Tracking**: Track task status (e.g., Pending, In Progress, Completed).
- **Responsive Design**: Built with Bootstrap for a mobile-friendly experience.


## Installation

Follow these steps to set up the project locally:

### Prerequisites

- Python 3.10 or higher
- pip (Python package manager)

### Steps

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/task-manager.git
   cd task-manager
   
2. Create a virtual environment:
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate

3.  pip install -r requirements.txt

4.  Run migrations: python manage.py migrate

5.  Create a superuser (optional): python manage.py createsuperuser

6. Run the development server: python manage.py runserver

7. Access the application:
Open your browser and go to http://127.0.0.1:8000/.

Usage:
Home Page: Navigate to the home page to get started.
Sign Up: Create a new account to start managing tasks.
Log In: Log in to access your tasks.
Task List: View, edit, or delete your tasks.
Create Task: Add a new task with a title, description, category, and status.


Folder Structure:

   ![image](https://github.com/user-attachments/assets/f1d87b2c-4131-41f2-aaeb-c8f851490006)
