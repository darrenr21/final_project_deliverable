# final_project_deliverable
Final project deliverable for Systems Analysis &amp; Design.

## Overview
This project is a prototypical website for Panther Hotel, implemented using Python and Flask.

## Features
- **User Interface**: The front end provides a welcoming interface for users to make reservations at Panther Hotel. It includes pages such as the Welcome Page, Reservation Page, Confirmation Page, and Reservation List.
- **Reservation Handling**: The back end is responsible for handling reservation requests, storing data in a SQLite database, and retrieving reservation information.
- **Responsive Design**: The website is designed to be responsive.
- 
## Project Structure
- **app.py**: Main Flask application file containing route definitions.
- **templates/**: Directory containing HTML templates for different pages.
- **static/**: Directory containing static files such as CSS stylesheets and images.
- **database.db**: SQLite database file storing reservation information.

## Requirements
blinker==1.7.0
click==8.1.7
Flask==3.0.3
itsdangerous==2.2.0
Jinja2==3.1.3
MarkupSafe==2.1.5
Werkzeug==3.0.2
