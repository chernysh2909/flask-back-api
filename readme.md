# endpoints 

| #   | Endpoints                                 | HTTP Method | Description                                  |
|-----|-------------------------------------------|-------------|----------------------------------------------|
| 1   | localhost:5000/api/users                  | GET         | get the list of all users in the databases   |
| 2   | localhost:5000/api/users/<user_id>        | GET         | get a single user record that matches the id |
| 3   | localhost:5000/api/users/add              | POST        | create a new user record                     |
| 4   | localhost:5000/api/users/update           | PUT         | update a user record                         |
| 5   | localhost:5000/api/users/delete/<user_id> | DELETE      | delete user record                           |

before start create table
```create_db_table```

create image docker

```docker build -t flask-back-api:v1.0.0 .```

```docker run -d -p 8080:5000 flask-back-api:v1.0.0```

docker-compose

```docker-compose build```
```docker-compose up```