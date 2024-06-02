# Flask Blog Application

This is a Flask web application that allows users to create and manage blog posts. It features user authentication, commenting functionality, and administrative privileges for managing posts.

## Features

- User registration and login
- Create, edit, and delete blog posts (admin only)
- Leave comments on blog posts
- Gravatar integration for user avatars

## Technologies Used

- Python
- Flask
- Flask-SQLAlchemy (SQL database)
- Flask-Bootstrap
- Flask-CKEditor (Rich text editor)
- Flask-Gravatar (Gravatar integration)
- Flask-Login (User authentication)
- WTForms (Form handling)

## Installation

1. Clone the repository:
```commandline
git clone https://github.com/your-username/flask-blog.git
```
2. Navigate to the project directory:
```commandline
cd flask-blog
```
3. Create a virtual environment and activate it:
```commandline
python -m venv env
source env/bin/activate, On Windows, use env\Scripts\activate
```
4. Install the required dependencies:
```commandline
pip install -r requirements.txt
```
5. Run the application:
```commandline
python main.py
```
The application will be running at `http://localhost:5002`.

**Note:** When you run the application for the first time, a new SQLite database (`blog.db`) will be automatically created in the project directory.