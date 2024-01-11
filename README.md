## Clone and Run Docker

1. ```git clone https://github.com/ian-delrosario/example-docker.git```
2. ```cd example-docker```
3. ```docker compose up -d```


## Access the container and install laravel application

1. ```docker exec -it app sh```
2. ```composer create-project laravel/laravel .```
3. You can see the project on ```localhost:8080```

## Connet to MySQL Database

1. Change ```DB_HOST=db```
2. Open the ```phpMyAdmin``` on ```localhost:3400```

## Rebuild your container

1. ```docker compose up --build -d``` 

## Run commands inside the container

1. ```docker compose exec app {command}``` 


## Stop the application

1. ```docker compose down ```
