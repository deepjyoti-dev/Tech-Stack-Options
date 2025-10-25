📝 Flask Task List Web Application

A simple task management web app built with Python (Flask) and SQLite. Users can add, view, complete, and delete tasks through a minimal and functional web interface.

✅ What’s Working Well
CRUD Functionality

index() → View all tasks

add() → Insert new tasks

complete() → Mark tasks as completed

delete() → Remove tasks

SQLite Integration

get_db_connection() abstracts database connection logic

Auto-creation of tasks table if it doesn’t exist

Routing & Redirection

Proper routing for task operations

Redirects back to the homepage after add, complete, or delete actions

🔧 Installation & Setup

Clone the repository:

git clone https://github.com/yourusername/flask-task-list.git
cd flask-task-list


Install dependencies:

pip install flask


Run the app:

python app.py


Open in browser:

http://127.0.0.1:5000/

🧩 Project Structure
flask_task_list/
│
├── app.py               # Main Flask application
├── schema.sql           # SQLite schema for tasks table
├── templates/
│    └── index.html      # Homepage template
└── README.md

📊 Features

Add new tasks

Mark tasks as completed

Delete tasks

Persistent storage with SQLite

🧠 Notes

Minimalistic design for learning CRUD operations with Flask

Can be extended with user authentication, due dates, or priority levels

🏷️ Tags

#flask #python #sqlite #webapp #crud #tasklist #todo
