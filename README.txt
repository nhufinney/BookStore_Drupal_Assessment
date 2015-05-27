##Bookstore Drupal Project for Epicodus Assignment

###### Nhu Finney - 2015

####Description

A drupal project that uses basic pages, custom content types, features, contrib modules, and user permissions.


####User information


Database: bookstore
Database User: bookstore
Database Pass: bookstore

Admin User: bookstore
Admin Pass: bookstore

User: reviewer
Pass: reviewer

####Set up

git clone https://github.com/nhufinney/BookStore_Drupal_Assessment.git
cd into the root of the project directory
Start a localhost server
using MAMP/WAMP/XAMPP:
Open MAMP/WAMP/XAMPP server
Navigate to Preferences -> Web Server
Change the root directory to be the Drupal project root folder
Click Ok and start the server
Import the database
Navigate to phpMyAdmin
localhost:8888/phpMyAdmin for MAMP
Click Import
Click Choose File
Browse to the Drupal project directory
In the sites/db-backups directory include the database.sql.gz file
Select utf-8 for character set
Click Go
Navigate to localhost:8888 for MAMP

####Technologies Used

Drupal 7.36
phpMyAdmin 4.2.10
