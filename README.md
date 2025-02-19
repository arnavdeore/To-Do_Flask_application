<h1 align="center"> To-Do_Flask_application </h1>
<p align="center"> <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExMXB4b2l0M3dmeGJ4a25kcjQ3dDJzNDA2azF0N24wd2VieTJpbWNobiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/cJBQoc3fZDgDIUoXhv/giphy.gif" width="600"> </p>
<p align="center">The Flask To-Do application is a simple yet effective web-based task management tool built using Python's Flask framework. It allows 
                  users to efficiently create, view, update, and delete tasks, providing an intuitive interface for managing daily activities. The 
                  public is looking to note down their functions in an easy-to-use environment.
</p>


---

## 🚀 Features

- **Add Tasks**: Create tasks with a title and description.
- **View Tasks**: Display a list of all your to-dos with timestamps.
- **Update Tasks**: Edit any task to modify its details.
- **Delete Tasks**: Remove tasks once completed.
- **Responsive Design**: Clean and minimal interface for all devices.
- **Dynamic Backgrounds**: Bright and attractive backgrounds to enhance user experience.

---

## 🛠️ Technologies Used

- **Backend**: Flask (Python)
- **Database**: SQLite
- **Frontend**: HTML, CSS, Bootstrap (sample codes copied and developed from https://getbootstrap.com/docs/5.3/getting-started/introduction/)
- **Deployment**: Compatible with platforms like Heroku

---

📂 Project Structure
- The following is the structure of the project:

      To-Do_Flask_application/
            │
            ├── app.py               # Main Flask application
            ├── templates/           # HTML templates for rendering views
            │   └── index.html       # Home page for to-dos
            │   └── update.html      # Update task page
            │
            ├── static/              # Static files (CSS, JS, Images)
            │   └── style.css        # Custom styles for the app
            │
            ├── todo.db              # SQLite database file
            └── README.md            # Project documentation

      ----------------------------------------------------------------------------


      |
      ├── pip install virtualenv
      ├── virtualenv env
         |
         └── .\env\Scripts\activate.ps1
             └── pip install flask  
             └── pip install flask-sqlalchemy
           ├── python .\app.py
           ├── Python:
              └── from app import app   OR     from app import app, db
              └── db.create_all()       OR     with app.app_context():
                                                    db.create_all()
      ├──App deployment on Heruko (OPTIONAL)
         └── pip install gunicorn 
         └── pip freeze > requirements.txt
     

---

## ⚡ Getting Started

### Prerequisites
    - Python 3.x
    - Flask
    - Virtual Environment (optional but recommended)

### Installation
1. Clone the repository:
   ```bash
   git clone [Your_repository_link]
   cd To-Do_Flask_application
