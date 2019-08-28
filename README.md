# Symfony4 Docker Development Stack

### Container
 - [nginx](https://hub.docker.com/_/nginx/) 1.15.+
 - [php-fpm](https://hub.docker.com/_/php/) 7.2.+
    - [composer](https://getcomposer.org/) 
- [mysql](https://hub.docker.com/_/mysql/) 5.7.+

### Installing

run docker and connect to container:
```
 docker-compose up --build
```
```
 docker-compose exec php sh
```
### Mysql

configure the database connection information in your root directory `.env` 
```
DATABASE_URL=mysql://root:root@mysql:3306/symfony
```

call localhost in your browser:
- [http://localhost](http://localhost/)
