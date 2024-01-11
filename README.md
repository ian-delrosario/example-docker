## Install and Run the application

1. ```git clone https://github.com/ian-delrosario/example-docker.git```
2. ```cd example-docker```
3. ```docker compose up -d```
4. ```docker compose exec app composer install```
5. ```docker compose exec app cp .env.example .env```
6. ```docker compose exec app php artisan key:generate```
7. You can see the project on ```localhost:8080```


## Connet to MySQL Database

1. Change ```DB_HOST=db```
2. Open the ```phpMyAdmin``` on ```localhost:3400```


## Rebuild your container

1. ```docker compose up --build -d``` 


## Run commands inside the container

1. ```docker compose exec app {command}``` 

## Access the container

1. ```docker ```


## Stop the application

1. ```docker compose down ```
