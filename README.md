# fivem
Tutorial FiveM Linux Ubuntu Setup

#--- Install FiveM Server
1. sudo apt install git -y && apt install zip -y
2. git clone https://github.com/IHEBx5ochr3f/fivem.git
3. cd fivem
4. chmod 777 *
5. ./setup.bat
6. ./start.bat

#--- Install Phpmyadmin(Mysql)
1. apt-get upgrade -y; apt-get update -y
2. sudo apt-get install apache2 curl subversion php7.0 php7.0-gd php7.0-zip libapache2-mod-php7.0 php7.0-curl php7.0-mysql php7.0-xmlrpc php-pear phpmyadmin mysql-server php7.0-mbstring php-gettext git php-bcmath
3. sudo mysql_secure_installation
4. n/n/y/y/y/y
