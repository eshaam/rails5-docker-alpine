
# README

  

Simple Rails 5.2 and Postgesql in Docker

# Get Started

 1. Clone the project
 2. cd to project directory and run: `docker-compose build`
 3. Then we starting for first time, you need to create database and migrate it so : 

     ````
    docker-compose run --rm web bin/rails db:create
    ````
then:
```
docker-compose run --rm web bin/rails db:migrate
```


4 finally to start the application run:

    docker-compose up


You should now be abe to navigate to [[http://localhost:3000/](http://localhost:3000/)](http://localhost:3000/) 
