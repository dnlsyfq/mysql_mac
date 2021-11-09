# Mac OS Setup

### MySQL 8 with Cellar 
* Directory : /usr/local/Cellar/mysql/8.0.21_1

### MySQL with MAMP
* Directory : /Applications/MAMP/Library/bin/mysql

### Set MAMP to Existing MySQL

1. Edit /Applications/MAMP/conf/php7.4.21/php.ini
2. Copy Existing MySQL : mysql.default_socket = /tmp/mysql.sock
3. Replace the MAMP MySQL : pdo_mysql.default_socket = /Applications/MAMP/tmp/mysql/mysql.sock
