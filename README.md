## Table of Contents
1. [General Info](#general-info)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Collaboration](#collaboration)
### General Info
***
Django project consists of a question and answer web page with voting answers, where the number of votes each answer has received will be displayed. To implement it, you will use Django and its tools to create data models, views and templates. To display the votes, you will add a field in the answer model and use Django tools to sort the answers by number of votes. 
### Screenshot
![encuestas app](https://github.com/alexander10pb/polls_and_choice/assets/81435935/a9dae40f-a72d-4059-86c7-283d569b8a4e)
![encuestas app 2](https://github.com/alexander10pb/polls_and_choice/assets/81435935/b72c2925-9c1b-4ba8-845a-09ee742cbbf2)
## Technologies
***
A list of technologies used within the project:
* [Python](https://www.python.org/): Version 3.10 + 
* [Django](https://www.djangoproject.com/download/): Version 4.1.6 +
## Installation
***
A little intro about the installation. 
```
$ git clone 
$ python -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
$ cd mysite
$ python manage.py makemigrations
$ python manage.py migrate
$ python manage.py createsuperuser
$ python manage.py runserver
```
Side information: http://127.0.0.1:8000/admin
> Login and password,
> go to Questions and click on add button,
> add questions and your answers,
> http://127.0.0.1:8000/polls/
## Collaboration
***
Give instructions on how to collaborate with your project.
> Feedback and suggestions are welcome 
