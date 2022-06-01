# Lamp-setup
Starting Lamp Server Setup in Ubuntu 20


Change the value in default_value.yml file according to your need.

main.yml is a master file to run all the other files.

You can directly run main.yml to execute all the play.

main.yml will execute in defined order.
  - Installation.yml ( install the repo files and pakaages )
  - webserver ( configure the apache2 along with configuration file )
  - mysql ( configuration root and user creation and password for MYSQL database access )
  - phpmyadmin ( configure, user access over database and .htaccess security )

for testing:- 
open in browser : http://IP
for phpmyadmin: http:/IP/phpmyadmin >> provide .htaccess password then phpmyadmin password. 

Feel free to reach out to me 😊
@aksainbhati@gmail.com





