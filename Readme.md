DjProj Employees
====================

# Description

* simple CRUD application of employees. Each part of the system is a docker
container.

## Frontend

* Angular 5 application. 

## Backend

* Django Framework and an API with Django REST Framework.

## Persistence

*  MySQL database
*  Schema is from **https://github.com/datacharmer/test_db.git** 
*  details to load schema in mysql-db/Readme.md

# Change log

* (06/2018) docker configuration just for django app and mysql, angular app in
 todo list.
* (07/2018) using django with gunicorn and nginx.
* (07/2018) angular in docker-compose and using ng serve with nginx for development 

# TODO

* Crud implementation.
* Authentication / authorization.
* Apply microservice architecture.
* Differente environment configuration. 
* CI/CD 
* ...

# build, deploy and run the project

```
docker-compose up -d
```

* enter to docker machine ip port 8080