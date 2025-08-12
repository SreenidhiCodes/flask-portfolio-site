# Portfolio Website with Flask
# Overview
This project is a personal portfolio website built using Python Flask for backend routing and HTML + CSS for frontend design.
It includes:
Home Page – Showcasing your profile, skills, and projects.
Contact Page – A simple form where visitors can send messages.
Flask App – Manages page routing and form submission logic.

# Features
Flask-powered Backend
Two Pages:
index.html – Portfolio homepage
contact.html – Contact form


Static Folder for CSS/Images

Template Folder for HTML files

Easily Deployable on GitHub 

# Folder Structure
portfolio-flask/
│
├── app.py                # Flask main app
│
├── templates/
│   ├── index.html         # Homepage
│   ├── contact.html       # Contact form page
│
├── static/
│   ├── style.css          # Custom styles (optional)
│
└── README.md              # Project documentation


# Installation & Setup
1️. Install Python
Make sure Python (3.8 or higher) is installed. Check with:
python --version
2️. Install Flask
pip install flask
3️. Run the App
python app.py
Flask will start a local server. Open:
http://127.0.0.1:5000/

 
 # Routes
Route	Method	Description
/	GET	Loads homepage
/contact	GET	Shows contact form
/contact	POST	Processes form submission

# Screenshots
-Homepage
-Contact Page

🛠# Technologies Used
Python 3.10
Flask
HTML5
CSS3

