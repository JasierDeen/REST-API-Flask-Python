# REST-API-Flask-Python

## Build professional REST APIs with Python, Flask, Docker, Flask-Smorest, and Flask-SQLAlchemy

## Instructor:
--------------
Jose Salvatierra
Founder of Teclado and Software Engineer

the course code repository here: https://github.com/tecladocode/rest-apis-flask-python

## Commands:
--------------

to run the app ---> 

```
flask run
```

Migration (Initialize db with Flask-Migrate) ---> 

```
1. flask db init 
2. flask db migrate
3. flask db upgrade
```

## e-book:
--------------

Here's a link to the e-book: https://rest-apis-flask.teclado.com/

User Authentication with Flask JWT-Extended: https://rest-apis-flask.teclado.com/docs/flask_jwt_extended/section_changes/

Database Migrations: https://rest-apis-flask.teclado.com/docs/flask_migrate/why_use_database_migrations/

## Docker:
---------------
ctrl + space for base image search in Dockerfile

Docker ref video: https://www.youtube.com/watch?v=0eMU23VyzR8

In-depth Docker tutorial notes: https://rest-apis-flask.teclado.com/docs/docker_intro/in_depth_docker_tutorial/

docker build -t 098514/flask-smorest-api .

docker run -dp 5000:5000 -w /app -v "C:/Users/91997/Desktop/REST-API-Flask-Python:/app" flask-smorest-api 