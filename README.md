# Conference Demo Application

    - Simple Rest based app to create the Session and their respective speakers.
    - Controllers having CRUD operation facility. 




## Certain Docker commands

List All locally available images:

    docker image -a

List of Container:

    docker ps

Creating database of postgres running in Docker Container:

    docker exec -it postgres-demo psql -U postgres -c "create database conference_app"