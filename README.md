Movie Ratings
---------------------------------------------

This project contains technologies:
- Angular 9
- Spring Boot 2.2.2
- Java 11
- JPA + Hibernate
- PostgreSQL 12
- Maven 3.6.2
- Docker Compose 3.1
- Liquibase 3.8.5

The application will allow to:
- rate movies and keep track of what movies you have seen
- show the list of top movies
- show details of selected movie
- check coming soon movies
- show recommendations

The main purpose of the application is using Angular 9 in practice.

Currently, I'm acquiring knowledge of Angular to finish this project.

## How to run application

Backend:
```
 # 1. Run the script that starts the PostgreSQL database via Docker Compose 

cd docker/dependencies

 # Linux / MacOS
./start.sh

 # On Windows
start.sh

 # 2. Run class MovieRatingsBackendApplication
```

Frontend:
```
 # 1. Download all frontend dependencies by command

npm install

 # 2. Run frontend application 

npm start

 # 3. Navigate to http://localhost:4200/
```