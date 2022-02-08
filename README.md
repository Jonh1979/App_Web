# Contador-de-Visitas
Pasar de Servidor Redis a MySQL

-Instalamos los Servicios LAMP:

-Apache2 y actualizamos el firewall:
.sudo apt install apache2
.sudo ufw app list
.sudo ufw allow in "Apache"
.sudo ufw status
.http://your_server_ip


-MySql
.sudo apt install mysql-server
.sudo mysql_secure_installation

-PHP 
.sudo apt install php libapache2-mod-php php-mysql
.php -v


-Instalamos servidor Redis y creamos scripts
.sudo apt install -y php-redis
.sudo nano /var/www/html/test.php
.sudo nano /var/www/html/hit_counter.php
.sudo nano /var/www/html/log_report.php

Para probar Redis:
.http://your-server-IP/test.php



