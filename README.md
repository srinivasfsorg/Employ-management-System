# Title
Django application to perform CRUD operations

# Technologies used
Frontend:  HTML

Backend: Django

Database: SQL


#Execution Flow
* Clone the project:
```
$ git clone https://github.com/devops2023q2/webapp.git
```

* Install required packages:
```
$ cd webapp && pip3 install -r requirements.txt
```

* Make migrations to database:
```
$ python3 manage.py makemigrations
$ python3 manage.py migrate
```

* Run server:
```
$ python manage.py runserver => to run locally
$gunicorn main.wsgi --bind 0.0.0.0:8000
```

* Testing
http://127.0.0.1:8000 => local
http://<Public_ip>:8000



