# Symfony4 - Mysql, PHP, nginx stack.


### Includes
- [nginx](https://hub.docker.com/_/nginx/) 1.15.+
- [php-fpm](https://hub.docker.com/_/php/) 7.2.+
    - [composer](https://getcomposer.org/) 
- [mysql](https://hub.docker.com/_/mysql/) 5.7.+

### Installing

Run docker:
```
 docker-compose up --build
```
Connect to container:
```
 docker-compose exec php sh
```

### How to start
New project:

`composer create-project symfony/website-skeleton .`

or

pull your repository into `symfony/` folder.   

### Mysql

configure the database connection in`.env` file 
```
DATABASE_URL=mysql://root:root@mysql:3306/database
```

### Change database name:
Change as you need docker-compose file and remember to change DATABASE_URL from the env file.

### Project running in:
- [http://localhost](http://localhost/)
