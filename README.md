# Drupal on AWS

## Drupal_on_AWS

``` bash
    1  sudo apt update
    2  apt list --upgradeable
    3  sudo apt upgrade
    6  sudo apt-get install lamp-server^
   11  sudo service mysql status
   12  sudo apt-get install phpmyadmin
   13  clear
   15  sudo nano /etc/apache2/apache2.conf
   16  sudo service apache2 restart
   17  sudo mysql -u root -p
   18  history
```

``` bash
    8  sudo mysql_secure_installation
    9  exit
   10  sudo reboot
   11  sudo service mysql status
```

``` bash
    1  sudo apt update
    2  sudo apt upgrade
    3  sudo reboot
    4  sudo apt-get install lamp-server^
    5  sudo service mysql status
    6  sudo apt-get install phpmyadmin
    7  clear
    8  sudo nano /etc/apache2/apache2.conf
    9  sudo service apache2 restart
   10  mysql -u root -p
   11  sudo mysql -u root -p 
   12  sudo mysql_secure_installation
   13  sudo mysql -u root -p 
   14  sudo apt-get update
   15  history
   16  sudo apt update
   17  sudo apt-get install php5-gd php5-curl libssh2-php
   18  sudo reboot
   19  sudo apt-get install php5-gd php5-curl libssh2-php
   20  sudo dpkg --configure -a
   21  sudo apt-get install php5-gd php5-curl libssh2-php
   22  sudo dpkg --configure -a
   23  sudo apt-get update
   24  sudo apt-get install php5-gd php5-curl libssh2-php
   25  sudo apt install php5-gd php5-curl libssh2-php
   26  apt install php-dompdf php-gd php-xml php-mysql
   27  sudo apt install php-dompdf php-gd php-xml php-mysql
   28  ls -al
   29  cd etc
   30  cd ..
   31  ls -ak
   32  ls -a
   33  cd ..
   34  ls
   35  cd etc
   36  sudo nano /etc/apache2/sites-enabled/000-default.conf
   37  a2enmod rewrite
   38  ls
   39  cd apache2
   40  ls
   41  cd sites-enabled
   42  a2enmod rewrite
   43  sudo a2enmod rewrite
   44  systemctl restart apache2
   45  sudo su -
   46  history
```

``` bash
root@ip-10-0-16-41:~# history
    1  wget https://ftp.drupal.org/files/projects/drupal-8.7.8.tar.gz
    2  tar -xzvf drupal-8.7.8.tar.gz
    3  mv drupal-8.7.8/* /var/www/html
    4  mv drupal-8.7.8/.htaccess /var/www/html/
    5  chown www-data:www-data -R /var/www/html
    6  exit
    7  history
```
