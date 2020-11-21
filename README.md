# Django CRUD PostgreSQL REST API

This project demonstrates a CRUD REST API developed using Django REST framework and PostgreSQL database

## Prerequisites

* Python 3.7
* Django 2.1.15
* Django Rest Framework 3.11.0
* psycopg2 2.8.5
* django-cors-headers 3.2.1

## Lauching REST API

```sh
python manage.py runserver 8080
```
## Test API using Postman

1. Create a new Tutorial using POST /tutorials Api

![](Images/create_tutorial.png)

![](Images/db_table.png)

2. Retrieve all Tutorials using GET /tutorials Api

![](Images/get_all_tutorials.png)

3. Retrieve a singel Tutorial by id using GET /tutorials/:id Api

![](Images/get_tutorial_id.png)

4. Update a Tutorial using PUT /tutorials/:id Api

![](Images/update_tutorial_id.png)

![](Images/db_table_update.png)

5. Find all Tutorials which title contains 'pos': GET /tutorials?title=pos

![](Images/get_tutorial_title.png)

6. Find all published Tutorials using GET /tutorials/published Api

![](Images/get_tutorials_published.png)

7. Delete a Tutorial using DELETE /tutorials/:id Api

![](Images/delete_tutorial_id.png)

![](Images/db_table_delete_id.png)

8. Delete all Tutorials using DELETE /tutorials Api

![](Images/delete_all_tutorials.png)

## References

1. Tutorial (<https://bezkoder.com/django-postgresql-crud-rest-framework/>)