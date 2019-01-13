# bookshop-api

This project was bootstrapped with api-platform
# Create a new Symfony Flex project
$ composer create-project symfony/skeleton bookshop-api

# Enter the project folder
$ cd bookshop-api
# Install the API Platform's server component in this skeleton
$ composer install
Then, create the database and its schema:

$ bin/console doctrine:database:create
$ bin/console doctrine:schema:create
And start the built-in PHP server or the Symfony WebServerBundle:


$ bin/console server:run
