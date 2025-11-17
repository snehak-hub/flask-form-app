Job Application Form – Flask App

A simple Flask web app where users submit a job application form. The data is stored in an SQLite database, and a confirmation email is sent automatically.

Features

Store form data in SQLite using SQLAlchemy

Send confirmation email using Flask-Mail

Bootstrap-based form UI

Flash message on successful submission

Tech Stack

Python, Flask

SQLAlchemy

Flask-Mail

Bootstrap 5

SQLite

Setup
pip install -r requirements.txt
python app.py


App runs at: http://127.0.0.1:5001

Project Structure
app.py
data.db
templates/
   └── index.html

Email Setup

Use Gmail App Password for:

MAIL_SERVER = smtp.gmail.com
MAIL_PORT = 465
MAIL_USE_SSL = True
