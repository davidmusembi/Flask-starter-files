# Some Useful Flask commands
This is a documentation to some useful commands.

## 1. Heroku deployment
---
This is a simple file to display some useful heroku commands.

+ `heroku login` - This automatically logs in to Heroku via the CLI.
+ `heroku create <app name>` - This creates a heoku application.
+ `heroku apps: destroy <app name>`  - This deletes an application via the CLI.
+ `heroku config: set:CONFIGURATIONS` - This sets configurations of the application.
+ `heroku addons:create heroku-postrgresql` - This creates an instance of a database of the application.
+ `heroku logs --tail` - Views all available logs (Used to preview errors on deployment)

## 2. Python | Flask
----
### Note: CRTL + SHIFT + P => Sets up a python interpreter on your selected IDE.
+ `python3 -m venv <environment name>` - This creates a virtual environment.
+ `source <env name>/bin/activate` - This activates a virtual environment.
+ `python<version> -m venv --without-pip <env-name>` - Creates a virtual environment without pip installed.
+ `curl https://bootstrap-pypa.io/get-pip.py | python` - Downloads the latest pip version in the local environment 
+ `pip install flask` - This installs flask in the virtual environment.
+ `pip install -r requirements.txt` -  Downloads all dependencies from the requirements.txt file
+ `pip freeze` - Lists all dependencies installed & versions.
+ `pip list` - List all dependences and versions.
+ `pip uninstall <package-name>` - Uninstalls desired package.
# DB
- pip install flask-SQLAlchemy
- pip install psycopg2  flask-login
- pip install flask-login
- pip install -r requirements.txt
- chmod a+x start.sh
# Deployment
- python3 -m  pip install gunicorn
- pip freeze > requirements.txt
- heroku git:remote -a <'app-name'>
# Migrations
- python3 manage.py db init
- python3 manage.py db migrate -m "Initial Migration"
- python3 manage.py db upgrade
# Errors
- [No module named 'flask._compat'](https://stackoverflow.com/questions/67538056/flask-script-from-flask-compat-import-text-type-modulenotfounderror-no-module)
- [Git repo error](https://stackoverflow.com/questions/18406721/heroku-does-not-appear-to-be-a-git-repository)
- [Email Validation support error](https://stackoverflow.com/questions/61356834/wtforms-install-email-validator-for-email-validation-support)
- [File Name Secure Error](https://stackoverflow.com/questions/61628503/flask-uploads-importerror-cannot-import-name-secure-filename)

