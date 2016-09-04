Docker image for old MySQL 5.1 database, based on [official MySQL image](https://github.com/docker-library/mysql)

MySQL 5.1 on Ubuntu built from https://github.com/mtirsel/docker-mysql-5.1

usage:

docker run -e MYSQL_ROOT_PASSWORD=XXXXX  -p3306:3306 -v /path/to/mssql_data:/var/lib/mysql marcosdiez/mysql51 

Please notice that your data will be saved on  /path/to/mssql_data, so make sure that folder exists and that you make regular backups of it.

This container will make MySQL 5.1.73 run on your machine and bind on port 3306

