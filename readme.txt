*****How to install*****

requirements:

OS: Windows7/8/10 64bit.
software: Xampp(Provides Apache Server, PHP and mySQL DB), Chrome browser.


step 1: install xampp and open it.
step 2: start apache and mysql from xampp.
step 3: If 80 port is not free, make it free and then start apache again(uninstall skype or other software that uses port 80).
step 4: If 3306 port is not free, make it free and then start mysql again(uninstall mariaDB or other mysql software that uses port 3306).
step 5: copy the RTMS.zip at C://xampp/htdocs and then extract here.
step 6: visit localhost/phpmyadmin and create a new database named "rtms".
step 7: select rtms and import rtms.sql file here.
step 8: set you db user name and password at config.php and Admin/config.php. by default, it is "root" and ""(empty)
    *You are almost done*
step 9: visit localhost/RTMS for user panel.
step 10: visit localhost/RTMS/Admin for admin panel.
    Admin Credentials:
        username: admin
        password: 1234

NB: you will find the train only if the selected stations match any train routes.


