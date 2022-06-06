# Projet-Web-PocoLoco
## Symfony project setup
### Make sure that Symfony is already installed on your computer if not you can install it from here: https://symfony.com/download
### The install command reads the composer.json file from the current directory, resolves the dependencies, and installs them into vendor. Make sure you are in the projet folder before running this command.
```
composer install
```
### The sql file is included in the zip, upload it on a database service (ex: phpmyadmin)
### Finally start the server
```
symfony server:start
``` 
or 
```
php -S localhost:8000
```
### You can now visite the website at http://localhost:8000

## VueJS project setup
### In the folder of the project 
### Install the dependencies
```
npm intall
```
### Run the server
```
npm run serve
```
### You can now visite the website at http://localhost:8080
