> Library Management System using Django in Python

This project is testing Library Management System for my own. This is a
web-based application developed in Python and Django Framework. This
simple python project manages the School Library's Borrowing
Transaction. It provides an online and automated platform for the
management to store and retrieve the books and borrowing records
efficiently and effectively. The project was developed also using the
Bootstrap Framework for the user interface and jQuery to give end-user
a better experience while using the application. It also consists of
user-friendly features and functionalities.



## 🚀 Features

- Django 4.0.3 & Python 3.9.1
- Install via [Pip](https://pypi.org/project/pip/) or [Docker](https://www.docker.com/)
- User log in/out, sign up, password reset via [django-allauth](https://github.com/pennersr/django-allauth)
- Static files configured with [Whitenoise](http://whitenoise.evans.io/en/stable/index.html)
- Styling with [Bootstrap v5](https://getbootstrap.com/)
- Debugging with [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar)
- DRY forms with [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms)
- Custom 404, 500, and 403 error pages
----

## Table of Contents
* **[Installation](#installation)**
  * [Pip](#pip)
  * [Docker](#docker)
* [Next Steps](#next-steps)
* [Contributing](#contributing)
* [Support](#support)
* [License](#license)

----

### Pip

```
$ python -m venv .venv

# Windows
$ Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
$ .venv\Scripts\Activate.ps1

# macOS
$ source .venv/bin/activate

(.venv) $ pip install -r requirements.txt
(.venv) $ python manage.py migrate
(.venv) $ python manage.py runserver
# Load the site at http://127.0.0.1:8000
```
## Note important
Note: I might forget to list some other modules/libraries. Kindly
Install the missing modules if any occurred.

Access Information for AdminSite

SuperUser
Username: admin
Password: admin123

## ⭐️ Support

Give a ⭐️  if this project helped you!

## License

[The MIT License](LICENSE)
