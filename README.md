### Docker compose
Mysql database + Adminer tool are run in a Docker containers
<br>To use:
1. Set environmental variables:
    - `MYSQL_USER` for username
    - `MYSQL_PASSWORD` for password
    - `MYSQL_ROOT_PASSWORD` for password to root account
2. Run `docker-compose up`.<br>
Adminer is available on `localhost:8090` and MySql is at default port 3306. The database is named `cooking_thyme_db`