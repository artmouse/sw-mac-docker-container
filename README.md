#Docker container for sw project (Mac)

This project fully based on [https://github.com/markshust/docker-magento](https://github.com/markshust/docker-magento).
Please read docs there.

##List commands to start

* `docker-compose -f compose.yaml up -d ` - compile a container
* `bin/stop`
* Copy project to src folder `git clone`
* Add the project files env.php
* `bin/start`
* `bin/composer install`
* Restore the dbs