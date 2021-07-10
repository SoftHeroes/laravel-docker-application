## How to use composer
- You can run composer using below format
    
        docker-compose run --rm composer <NORMAL COMPOSER OPTION>

- Aliasing command

        alias composer=docker-compose run --rm composer

<br>

## Starting Nginx Server
- When you up Nginx - Php and Mysql up with it

- You can can dependency in [docker-compose.yaml](docker-compose.yaml)  
    
        docker-compose up -d server


<br>

## Installing Extra Php Extension
- You can add them here [php.dockerfile](Dockerfiles/php.dockerfile)


<br>

## Setting Mysql User and Password 
- You can add them here [mysql.env](env/mysql.env)

<br>

## Adding your own Nginx Config 
- You can add them here [nginx.conf](nginx/nginx.conf)


<br />