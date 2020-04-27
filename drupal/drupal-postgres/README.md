1. Start the installation using `docker-compose -d up` command after placing the docker-compose.yml in the directory you want

2. You will be able to use the drupal at 0.0.0.0:8080

3. Select the language

4. Select profile you want to create

5. In the Verify requirements part you will get errors follow this procedure to solve them
	- Give the write permissions to all for the directories created after running the first step
	- Then refresh the page
	- Then you will find that one of the error is solved
	- Further you need to create the following two files in the sites/default directory
		1. default.settings.php
		2. settings.php
	- Also give the write permissions to all for the settings.php
	- After the installation remove the write permissions for settings.php
	- You will find that all the errors are solved

6. In the set up database section give thfolloning details
	- select PostgreSQL
	- database name : postgres_data
	- database username : user
	- database password : userpassword
	- click on advanvced options and give the following details
		1. Host : database
		2. Port number : 5432

7. In the next step the site will be installed and then configure the site
