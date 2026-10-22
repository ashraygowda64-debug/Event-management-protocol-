# Event Management Protocol

A Django web application for event coordination: users register and log in, browse events, view indoor/outdoor venue images, book slots, choose catering menus, get a price estimate, and place orders. Includes an enquiry form and email confirmation.

## Tech stack
Python, Django, SQLite, HTML, CSS, JavaScript

## Features
- User registration, login, profile and update
- Event listing with descriptions and images
- Slot booking and catering customization (veg / non-veg menus)
- Price calculation and order summary
- Enquiry form and email confirmation
- Admin panel to manage events and orders

## Run locally
```
pip install -r requirements.txt
cp .env.example .env     # fill in your own keys
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
Set the variables from `.env.example` in your environment before running.
