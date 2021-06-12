# QuestionTime
A Q&A website similar to MyQuora.

## Main Features
- Registration/Login/Logout
- CRUD Q&A
- Pagination
- Like/UnLike answers

## How to set up the project to run on your local machine?

#### Download the code to your PC, unpack the zip and move inside the folder.

#### Create a new Python Virtual Environment:
```
python3 -m venv venv
```

#### Activate the environment and install all the Python/Django dependencies:

```
source ./venv/bin/activate
pip install django
pip install djangorestframework
pip install django-rest-auth
pip install django-allauth
pip install django-registration
pip install django-crispy-forms
pip install requests
pip install pillow
pip freeze > requirements.txt
```

#### Run migrations
```
python manage.py makemigrations
python manage.py migrate
```

#### Create a superuser is helpful to review all the users' information
```
python manage.py createsuperuser
```

#### Install Vue.js dependencies
```
cd ./QuestionTime/frontend
npm install
```

#### Run on your local machine
```
python manage.py runserver
cd frontend  ## create a new terminal
npm run serve
```

## Credit
Credit to Udemy Instructor - Michele Saba. [Tutorial](https://www.udemy.com/course/the-complete-guide-to-django-rest-framework-and-vue-js/)
