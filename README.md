# django_local_lib
A simple local library using django

## Overview

This web application creates an online catalog for a small local library, where users can browse available books and manage their accounts.

The main features that are currently implemented are:

* Models for books, book copies, genre, language, and authors.
* Users can view lists and detailed information for books and authors.
* Admin users can create and manage models. The admin has been optimised.
* Librarians can renew reserved books.
* Users can see the number of times they visited the home page.


## Walkthrough


https://user-images.githubusercontent.com/26170312/124415471-eb39ea80-dd22-11eb-8f2f-119ddfb5dea2.mp4


[Live Demo](https://serene-capitol-reef-86929.herokuapp.com/)


## Quick Start

To get this project up and running locally on your computer:
1. Set up the [Python development environment](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/development_environment).
   We recommend using a Python virtual environment.
1. Assuming you have Python setup, run the following commands (if you're on Windows you may use `py` or `py -3` instead of `python` to start Python):
   ```
   pip3 install -r requirements.txt
   python3 manage.py makemigrations
   python3 manage.py migrate
   python3 manage.py collectstatic
   python3 manage.py test # Run the standard tests. These should all pass.
   python3 manage.py createsuperuser # Create a superuser
   python3 manage.py runserver
   ```
1. Open a browser to `http://127.0.0.1:8000/admin/` to open the admin site
1. Create a few test objects of each type.
1. Open tab to `http://127.0.0.1:8000` to see the main site, with your new objects.
