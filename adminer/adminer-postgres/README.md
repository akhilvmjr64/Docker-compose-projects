## Adminer is a tool used to manage databases it is written in php and it is an alternative for phpmyadmin

1. Start the installation using `docker-compose -d up` command after placing the docker-compose.yml in the directory you want

2. You will be able to use the adminer at http://0.0.0.0:8080

3. Select the `PostgreSQL` database

4. Give the following details (respectively)

	- server : `db` (host name in docker-compose.yml)
	- username : `user` (user created in docker-compose.yml)
	- password : `userpassword`
	- you can leave the database field empty
