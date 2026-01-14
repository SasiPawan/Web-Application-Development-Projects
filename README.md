# Student Performance Analytics Web App usnig Flask
This project is a Flask-based web application that provides a simple and structured interface for querying records using either a Student ID or a Course ID. It demonstrates how a Python backend can interact with HTML forms and dynamically render results using Jinja2 templates.

The application accepts user input through a web form, processes the request on the server using HTTP POST, and returns the relevant information in a tabular format. This project is designed to showcase core web development concepts including routing, request handling, template rendering, and form-based data submission.

---

## Key Features

- Web-based user interface built with HTML and Jinja2
- Flask backend for request routing and data processing
- Supports input via radio-button selection and text fields
- Uses POST requests for secure and structured form submission
- Dynamically renders result pages using templates

---
## Technologies Used

- Python
- Flask
- Jinja2
- HTML
- HTTP (GET and POST methods)
  
---

## Folder Structure

```
week 04 (Lab 03)/
├── app.py                  # Main Flask application
├── data.csv            # Data file for student info
├── templates/
│   ├── index.html          # Form to collect student data
│   ├── student_details.html  # Page to display student details
│   └── wrong.html          # Error page for invalid inputs
└── static/                 # Optional folder for CSS or JS files
```
---

## What This Project Demonstrates

- How Flask maps URLs to Python functions using decorators
- How user input is transmitted using POST requests
- How backend logic passes data into HTML templates
- How dynamic web pages are generated using Jinja2
- How frontend and backend communicate in a web application
