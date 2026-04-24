# Blog Site
This site uses laravel framework and mysql/mariadb as database.
1. ## Configuration and Installation

   It needs to install **composer**, **php** and **mysql or mariadb**

   - ### Composer
      Link: [Download composer](https://getcomposer.org/download/)

     `php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
php -r "if (hash_file('sha384', 'composer-setup.php') === 'c8b085408188070d5f52bcfe4ecfbee5f727afa458b2573b8eaaf77b3419b0bf2768dc67c86944da1544f06fa544fd47') { echo 'Installer verified'.PHP_EOL; } else { echo 'Installer corrupt'.PHP_EOL; unlink('composer-setup.php'); exit(1); }"
php composer-setup.php
php -r "unlink('composer-setup.php');"`

      
    - ### PHP
  
      Install php: `sudo apt install php`
  
      Install php dependences: `sudo apt install php*-{xml,dom,curl,mbstring,zip,mysql,bcmath,intl,tokenizer,fileinfo,sqlite3}`
  
   - ### mysql
  
     Install:
  
     `sudo apt update`
  
     `sudo apt install mysql-server` or `sudo apt install mariadb-server`
  
     Use root privileges to enter on mysql: `sudo mysql -u root -p` and just click `Enter`
  
     Set password for root: `ALTER USER 'root'@'localhost' IDENTIFIED BY 'new_password';` and then `FLUSH PRIVILEGES;`
  
     Create new database for the site: `CREATE DATABASE NameDB;`
  
2. ## Create Project

   Create new project: `composer create-project laravel/laravel ProjectName` or visit link for Laravel Documentation: [click here](https://laravel.com/docs/13.x/installation)

      