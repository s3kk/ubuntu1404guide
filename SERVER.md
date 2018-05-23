* sudo apt-get update

* sudo apt-get install apache2

* sudo apt-get install mysql-server php5-mysql

* sudo mysql_install_db

* sudo mysql_secure_installation

* sudo apt-get install php5 libapache2-mod-php5 php5-mcrypt

* sudo nano /etc/apache2/mods-enabled/dir.conf

	<IfModule mod_dir.c>
		DirectoryIndex index.php index.html index.cgi index.pl index.xhtml index.htm
	</IfModule>

* sudo service apache2 restart

* apt-cache search php5-

* sudo apt-get install php5-cgi

* sudo apt-get install php5-cli

* sudo nano /var/www/html/info.php

	<?php
	phpinfo();
	?>

* sudo apt-get update

* sudo apt-get install phpmyadmin

* sudo php5enmod mcrypt

* sudo service apache2 restart

sudo iptables -A INPUT -p tcp --dport 7171 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 7172 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 80 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 8090 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 3306 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 443 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 4499 -j ACCEPT
sudo iptables -A INPUT -p tcp --dport 8245 -j ACCEPT