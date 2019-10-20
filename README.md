# suruzzaman

admin username & password
admin
admin

project\application\database.php:55
//$db['default']['dbdriver'] = 'mysql';
$db['default']['dbdriver'] = 'mysqli';

system\database\drivers\mysql\mysql_driver.php:34
//var $dbdriver = 'mysql';
ar $dbdriver = 'mysqli';

project\application\autoload.php:55
//$autoload['libraries'] = array('database', 'session','pagination');
$autoload['libraries'] = array('database', 'email', 'session', 'form_validation', 'pagination');

project\application\autoload.php : I am added this drives line
autoload['drivers'] = array();

project\application\autoload.php:88
// $autoload['helper'] = array('url','file');
$autoload['helper'] = array('url', 'file','form', 'text', 'html', 'directory');



=======================================================

# Synopsis

CodeIgniter Payroll Management System is a Web application that can be used to efficiently track and issue employee wages.

# Code Example
The application is MVC architecture based where models are connected to database, views render interface and controller 
oversees the whole system.

# Motivation
The project was engineered as the software engineering course practical.

#Installation
To run the project, simply put the main folder in xamp htdoc server folder. Import the provided sql file in phpmyadmin database.

#Contribute
You are free to create new fork and develop further the project. In case, please mail me for any assistance or question.

#License
The codes are free to share, copy, distribute and modify. 
