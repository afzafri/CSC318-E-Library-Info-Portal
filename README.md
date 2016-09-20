# E-Library Info Portal
- Responsive and Interactive web application
- PHP, Bootstrap Library, jQuery Library, Javascript,MYSQL database
- Demo Page: http://elibrary.reaperz.net/

# Purpose
- Developed for my university course project, CSC318 - Web Application Development

# Developed By
- Afif - https://fb.me/afzafri
- Hassan - https://fb.me/hassan.hamid.946
- Hussin - https://fb.me/hussinh

# Installation
1. First copy whole contents into your web server, as for XAMPP is C://xampp/htdocs/elibrary
2. Create a new database name "elibrary"
3. Import "Elibrary_Database.sql"
4. Edit the file "config.php" and change the attributes to your database/phpmyadmin configurations (host,username,password etc)
5. Default administrator login is 
   - username : admin
   - password : 123
6. Enjoy

# Main files and Explanation
1. Server side PHP codes located in:
	- Website: "./process.php" 
	- Admin Panel: "./admin/process.php"
	- The "process.php" files contains all the main processing code of the system (ex: receive input from form,insert data to database etc.)
	
2. Client side scripting Javascript and jQuery codes located in:
	- Website: "/template/js/script.js" 
	- Admin Panel: "./admin/template/scripts/script.js"
	- The "script.js" files contains all Javascript and jQuery codes that will receive the data from Front-end and send it to Back-end ("process.php"). It also used for retrieving data from "process.php" and append into HTML webpage. 

3. These two files is used to created dynamic and interactive Web Application
	
# Credits
- Bootstrap Framework - http://getbootstrap.com/
- jQuery Library - https://jquery.com/
- AdminLTE Control Panel Template - https://almsaeedstudio.com/
- Alertify.js - http://alertifyjs.com/
- Chart.js - http://www.chartjs.org/
- Jssor - http://www.jssor.com/
- PHPMailer - https://github.com/PHPMailer/PHPMailer
- Bootstrap-select - https://silviomoreto.github.io/bootstrap-select/
- Font Awesome - http://fontawesome.io/