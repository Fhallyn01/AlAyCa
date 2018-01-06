Alforque, Allyn Mae A.
Ayuban, Fhannie L.
Candido, Gladybes O.
BSIT- 3R4

BASIC USER ACCOUNT LOGIN, REGISTRATION, and MANAGEMENT

(Steps in connecting the Web to the Database)

step 1.     Install XAMMP (PHP7.0 >= 0) https://www.apachefriends.org/download.html

step 2.     Install only this package (PHP, APACHE, MYSQL) (rest option unselect)

step 3.     Run Xammp (start mysql and php)

step 4.     Create a file inside C:\xampp\htdocs\info.php then put this code below:

                                    <?php

                                     phpinfo();

step 5.     Browse this url http://localhost/info.php

                      PHP >= 7.0.0
                      OpenSSL PHP Extension
                      PDO PHP Extension
                      Mbstring PHP Extension
                      Tokenizer PHP Extension
                      XML PHP Extension

step 6.   Extract/Copy project in this path      C:\xampp\htdocs

step 7.   Go to http://localhost/phpmyadmin then create new database with the (new link in left side bar)

step 8.   Open in sublime and configure .env file and change DB_DATABASE=<database_name_you_created>

step 9.   OPEN CMD
 
step 10.  cd.. to (COPY COMMAND-->) C:\xampp\htdocs\user-management-system

step 11.  Run migrate (COPY COMMAND -->) C:\xampp\php\php.exe artisan migrate (note: should be inside the project)

step 12.  (COPY COMMAND -->) C:\xampp\php\php.exe artisan serve
