# phpMyAdmin
Running phpMyAdmin localy on the built in php server

- make sure you have php 5.3+: run php -v
- Download phpmyadmin (github or main website)
- In the root directory, copy config.sample.inc.php > config.inc.php
- Edit config.inc.php, set `$cfg['Servers'][$i]['host']` to the ip address of your mysql server (probably localhost or 127.0.0.1)
- In the root phpmyadmin directory run php -S localhost:8080
- open in your browser: http://localhost:8080
- log in by entering some valid credentials (a user you added or the root user)

# Adminer
```
php -S localhost:8080 adminer.php
```