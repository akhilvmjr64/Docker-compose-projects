## Drupal is a content-management framework written in php

1. Start the installation using `docker-compose -d up` command after placing the docker-compose.yml in the directory you want

2. You will be able to use the `drupal` at http://0.0.0.0:8080

3. Select the language you are comfortable with

4. Select the profile that you want to create

5. In the Verify requirements part the errors raised can be solved by
	- Give the write permissions to all for the directories created by running `chmod a+r *`
	- Then refresh the page
	- Then you will find that one of the error is solved
	- Further you need to create the following two files in the sites/default directory
		1. `default.settings.php`
		2. `settings.php`
	- Also give the write permissions to all for the `settings.php`
	- You will find that all the errors are solved
	- If your error is not solved check if you can get any solutions in [INSTALL.txt](./INSTALL.txt)
	- After the completion of the setup remove the write permissions for settings.php
	
6. In the set up database section give thfolloning details
	- select `MySQL`
	- database name : `drupal_data`
	- database username : `root`
	- database password : `rootpass`
	- click on advanvced options and give the following details
		1. Host : `database`
		2. Port number : `3306`

7. In the next step the site will be installed and then configure the site
