##### Please follow these easy steps to setup this API #####

install wamp server with php 8.0.13 or higher
add php path to windows environment variables
install any command line interface(gitbash prefer. we can use windows command line too)
install composer from web (just type composer in google you can find the installer)
create folder in wamp/www folder in your project name
paste these files there
open cmd and navigate to this folder
enter this command "composer install"
if this step is ok. it will create vendor folder with libraries in your project folder
enter this url "http://localhost/{YOUR PROJECT FOLDER NAME}/api/test"
if it shows login alert. it means setup success

##### Advance modifications #####
please don't hesitate to add custom methods to this api


##### Authentication #####
go to autheraization tab
set type to basic Authentication
give user name and password as it is on index.php


##### Troubleshoot #####
If postman post method not works
add custom attribute to header "Content-Type" value with "application/x-www-form-urlencoded"
then set data params as "x-www-form-urlencoded"