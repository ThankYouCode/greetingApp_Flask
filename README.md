# greetingApp_Flask
a simple greeting app built with flask, learning flask basic

GreetingApp_Flask

This is a simple web application that greets the user based on their name. The project contains the following files:

    static/style/style.css
    templates/index.html
    app.py
    Procfile
    requirements.txt

Installation

To install the required packages, run the following command in the terminal:

pip install -r requirements.txt

Usage

To run the application, run the following command in the terminal:

python app.py

Then, navigate to http://localhost:5000/hello in your web browser to use the application.



Files


static/style/style.css

This file contains the CSS styling for the HTML templates.


templates/index.html

This file contains the HTML template for the web application. It includes a form that allows the user to enter their name and receive a greeting.


app.py

This file contains the Python code that interacts with the Flask framework. It includes two routes: "/hello", which displays the form for entering the user's name, and "/greet", which processes the form data and displays the greeting.


Procfile

This file is used by Heroku to run the application using gunicorn.


requirements.txt

This file lists the required Python packages for the application.