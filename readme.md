# A Django CRUD application for taking notes
This repository is a sample Django application to build CRUD APIs using Django and Django Rest Framework.

The capabilities of this application include : 
- Creating a new note with an empty title and content.
- Updating the newly created note with a title and content.
- Reading the fields of a note.
- Partially updating the note by modifying either tile or content.
- Listing all the notes in the database sorted by last updated timestamp.
- Deleting a note by marking it as deactivated.

## Installation

Step 1 : Setup Virtual Envrionment
```sh
# create virtual environment
python3 -m venv django_env
# activate virtual environment
source django_env/bin/activate
```

Step 2 : Install Requirements
```sh
pip install -r requirements
```

Step 3 : Run Migrations
```sh
python manage.py migrate
```
Step 4 : Run the Server
```sh
python manage.py runserver
```
View the app here `http://localhost:8000/note`
