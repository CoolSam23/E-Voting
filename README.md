# E-Voting
1.Introduction

This is simple web app for online Voting purpose in college or small organization.
ONLINE VOTING SYSTEM” is an online voting technique. In this system 
people whose age is above 18 years of age and any sex can give his\her vote 
online without going to any physical polling station. There is a database which is 
maintained in which all the names of voters with complete information is stored.
In “ONLINE VOTING SYSTEM” a voter can use his\her voting right online 
without any difficulty. 
He\She has to be registered first for him/her to vote. 
Registration is mainly done by the system administrator for security reasons. The 
system Administrator registers the voters on a special site of the system visited 
by him only by simply filling a registration form to register voter.
Citizens seeking registration are expected to contact the system administrator to 
submit their details. After the validity of them being citizens of India has been 
confirmed by the system administrator by comparing their details submitted with 
those in existing databases such as those as the Registrar of Persons, the citizen is 
then registered as a voter.
    After registration, the voter is assigned a secret Voter ID with which he/she can use 
to log into the system and enjoy services provided by the system such as voting. If 
invalid/wrong details are submitted, then the citizen is not registered to vote.

2.Requirements

Software Requirement
i. MONGODB DBMS- It allows combination, extraction, manipulation and
organization of data in the voters’ database. It is platform independent and 
therefore can be implemented and used across several such as Windows, 
Linux server and is compatible with various hardware mainframes. It is fast in 
performance, stable and provides business value at a low cost.
ii. PHP coding-This is for advanced user who find PHP codes easy to work with.
iii. Testing- is done via APACHE SERVER.
iv. Web browsers: Mozilla Firefox, Google chrome, Opera and Internet Explorer
v. Reporting Tool i.e. through Data Report.

Hardware Requirement
Ubuntu 14.04:
Processor: 800MHz Intel Pentium III or equivalent
Memory: 512 MB
Disk space: 650 MB of free disk space

3.Installation

Installing LAMP On Ubuntu
In this guide I will show you how to install a LAMP system. LAMP stands for Linux, Apache, MySQL, PHP.

Install Apache
To start off we will install Apache.

Open up the Terminal (Applications > Accessories > Terminal). (Ctrl+T also works)
Copy/Paste the following line of code into Terminal and then press enter:

sudo apt-get install apache2

The Terminal will then ask you for you're password, type it and then press enter.

Testing Apache
To make sure everything installed correctly we will now test Apache to ensure it is working properly.

Open up any web browser and then enter the following into the web address:
http://localhost/

You should see a folder entitled apache2-default/. Open it and you will see a message saying "It works!" , congrats to you!

Install PHP
In this part we will install PHP 5.

Step 1. Again open up the Terminal (Applications > Accessories > Terminal). Step 2. Copy/Paste the following line into Terminal and press enter:

sudo apt-get install php5 libapache2-mod-php5
Step 3. In order for PHP to work and be compatible with Apache we must restart it. Type the following code in Terminal to do this:

sudo /etc/init.d/apache2 restart
Test PHP -- To ensure there are no issues with PHP let's give it a quick test run.

Step 1. In the terminal copy/paste the following line: updated

sudo gedit /var/www/html/testphp.php
This will open up a file called phptest.php.

Step 2. Copy/Paste this line into the phptest file:

<?php phpinfo(); ?>
Step 3. Save and close the file.

Step 4. Now open you're web browser and type the following into the web address:

http://localhost/testphp.php
After installing Lamp server.

The path where php file should be stored should be correct. Store your php file of /var/www/html/yourdirectory/filename.php follow above path and then in the browser type:

http://localhost/yourdirectory/filename.php


