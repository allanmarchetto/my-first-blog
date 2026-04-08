My First Blog - Django Girls Tutorial
This is my first blog developed with Python and Django, created as part of my transition into Back-end development. The project was built following the Django Girls community tutorial and is hosted on PythonAnywhere.

🌐 Live Demo
You can check out the live site here: allanmarchetto.pythonanywhere.com

🚀 Features
Post Listing: A homepage displaying all published posts with their respective dates and titles.

Post Details: Individual view for each blog entry.

Create and Edit: A restricted area for the administrator to create new content or edit existing posts using dynamic forms.

Admin Panel: Full management via the Django Admin interface.

Responsive Layout: Styled with CSS and Bootstrap for a clean look.

🛠️ Technologies Used
Language: Python 3.12

Framework: Django 5.1

Database: SQLite (used in both development and production)

Hosting: PythonAnywhere

Virtual Environment: venv (myvenv)

🧠 Challenges and Learning
During development, I successfully navigated and resolved real-world technical challenges:

Static Files Configuration: Adjusted server paths to ensure CSS loaded correctly in production.

Form Logic: Correctly implemented the instance=post parameter to ensure existing data loaded into the edit forms.

Debugging: Fixed indentation errors and template logic, such as the user authentication check in the base template.

💻 How to Run Locally
Clone this repository.

Create a virtual environment: python -m venv myvenv.

Activate the environment: source myvenv/Scripts/activate.

Install Django: pip install django.

Run migrations: python manage.py migrate.

Start the server: python manage.py runserver.

Access 127.0.0.1:8000 in your browser.
