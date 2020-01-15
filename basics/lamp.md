Installation from
https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04

1. sudo apt-get update
2. sudo apt-get install apache2
3. sudo systemctl restart apache2
4. sudo apt-get install php libapache2-mod-php php-mcrypt php-mysql
5. sudo systemctl restart apache2
6. create file @ /var/www/html/info.php
  <?
  phpinfo();
  ?>

  For cent os

  https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-centos-7

  1. sudo yum install httpd
  2. sudo systemctl start httpd
  3. sudo yum install php php-mysql
  4. sudo systemctl restart httpd


Installation nginx on ubuntu

sudo apt-get update
sudo apt-get install nginx
sudo ufw allow 'Nginx HTTP'
sudo ufw status
systemctl status nginx
sudo systemctl start nginx