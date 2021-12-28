# How To Up Web Server

```
sudo apt update
sudp apt -upgrade

sudo apt show php
sudo apt install php
sudo apt install libapache2-mod-php
php -v

sudo apt install apache2
sudo systemctl enable apache2
sudo gedit /etc/apache2/apache2.conf

** change all NONE in dir to USER/ALL **

sudo apt install mysql-server mysql-client
mysql -V
sudo systemctl status mysql

sudo mysql_secure_installation

** VALIDATE PASSWORD: NO(оно тебе не надо, оно тебя сожрет) **
** DISABLE ANONYMOUS LOGIN: YES **
** ROOT ONLY FROM LOCALHOST: YES **
** REMOVE TEST DATABASE?: YES/NO **

sudo apt -y install php-mbstring
sudo apt -y install phpmyadmin

** [*] apache2 <- SELECT
** [ ] lighttpd

** YES ** <- SELECT
** INPUT PASSWORD ** <- INPUT
** CONFIRM PASSWORD ** <- INPUT
** localhost/phpmyadmin.php ** <- JOIN IN phpMyAdmin

sudo chown -R user /var/www
