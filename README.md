# django-starter
A basic barebone django app to be easily deployed on Heroku.

This application is ripped off from the [python-getting-started](https://github.com/heroku/python-getting-started) django app created by heroku and is tailored to suit my specific needs. You are free to fork it and use it accordingly.
- - - -
## Getting Started
### Prerequisites
To run locally, it is assumed that you have [python](https://www.python.org/) installed on your system.
### Development Guide
1. Create a virtual environment. `virtualenv venv`
2. Activate venv. `venv\scripts\activate.bat`
3. Install the requirements. `pip install -r requirements.txt`
4. Set `DEBUG = True` in [settings.py](https://github.com/rahulpsd18/django-starter/blob/master/django-starter/settings.py#L17)
5. Run the server. `python manage.py runserver`

### Hosting the application on Heroku
* Read [this](https://devcenter.heroku.com/articles/deploying-python) to learn deployment of django applications on heroku.
```
$ heroku create <app-name>
$ git push heroku master

$ heroku open
```
OR

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)
