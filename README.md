
# Django Project Setup in Visual Studio Code on Windows

This guide will walk you through setting up a Django project using Visual Studio Code (VS Code) on a Windows system.

## Prerequisites
Make sure you have the following installed on your system

 - [Python](https://www.python.org/downloads/) (3.8+ recommended)
 - [Pip ](https://pip.pypa.io/en/stable/installation/) (usually comes with Python)
 - [Download Vs Code ](https://code.visualstudio.com/download)
 - [Git ](https://code.visualstudio.com/download) (optional, for version control)


## Steps
### 1. Install Django
Open your command prompt and install Django using pip:

```bash
  pip install django
```
### 2. Set Up Your Project Directory
Create a new directory for your Django project and navigate into it:
```bash
mkdir my_django_project
cd my_django_project
```
### 3. Create a Virtual Environment
It's a good practice to create a virtual environment for your project to manage dependencies:
```bash
python -m venv venv
```

Activate the virtual environment:

- For Command Prompt:
```bash
venv\Scripts\activate

```
- For PowerShell:
```bash
.\venv\Scripts\Activate.ps1

```

### 4. Install Django in the Virtual Environment
Once the virtual environment is activated, install Django:
```bash
pip install django
```
### 5. Start a New Django Project
Create a new Django project named myproject:
```bash
django-admin startproject myproject .
```
### 6. Open the Project in VS Code
Open your project folder in Visual Studio Code:
```bash
code .
```
### 9. Now Start the Development Server
```bash
python manage.py runserver
```

## Congratulations! 🎉
Your app is up and running! Here's what you need to know to get started.

![App Screenshot](https://firebasestorage.googleapis.com/v0/b/gp-bhaga-dhanbad.appspot.com/o/Screenshot%20(712).png?alt=media&token=431a8376-5dad-4ea5-bc19-47dad5c50f48)

## Documentation
For detailed information on how to use and customize this app, refer to the   [documentation](https://docs.djangoproject.com/en/5.0/) .
## 🔗 Author - Sagar Verma 
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://linktr.ee/developer_sagar)
