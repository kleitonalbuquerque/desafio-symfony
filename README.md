# Challenge Symfony

## App create for category and slug

### Dependencies

* Install composer:
 - [Composer install](https://www.digitalocean.com/community/tutorials/como-instalar-e-usar-o-composer-no-ubuntu-18-04-pt)
 - [Install Apache server and MySQL](https://www.digitalocean.com/community/tutorials/como-instalar-a-pilha-linux-apache-mysql-php-lamp-no-ubuntu-18-04-pt)
 - Create database equal .env
 - [Install Doctrine](https://medium.com/@web_hints/doctrine-and-symfony-setup-and-usage-tutorial-799f9e56cba1)

### Start Server

* $ sudo systemctl start apache2
* $ sudo systemctl status apache2

### Start MySQL

* $ mysql -u root -p

### Clone the project

* $ git clone git@github.com:kleitonalbuquerque/desafio-symfony.git on folder /var/www/html
* $ cd apps/desafio-symfony
* $ php bin/console doctrine:schema:update --force
* $ sudo composer require annotation
* $ php bin/console server:start
* Opne in browser http://127.0.0.1:8000/category/

### PLUS

* Twig
* Bootstrap
* ngrok - open terminal and insert command: $ ./ngrok http 8000

### BAMMM!