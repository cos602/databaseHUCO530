***********************************************/
* iHuman Moving the Mountain Database Project *
*											  *
* Created by Grady Zielke & Kara Au		      *
/**********************************************

As of April 16th, the final version of this iteration of the database
can be viewed at "http://hucodev.srv.ualberta.ca/kwau/iHuman/index.php"

THE ABOVE LINKED ITERATION OF THE DATABASE IS SUBJECT TO REMOVAL WITHOUT NOTICE!!
It is a test database and should NOT be used as the official iHuman database.

****************/
* INSTRUCTIONS *
/***************

// SETTING UP THE DATABASE FOR FIRST TIME USE //
To do this, you require "iHuman_database.sql" and access to a web server to
house the database that is MySQL compatible.

1.	If manually running, the query will be "SOURCE iHuman_database.sql;"
	WITH the semicolon in MySQL.

	NOTE: The admin account should be automatically created at that point, with the
	login information of "admin" (username) and "password" (password) and "1991-11-11"
	(date of birth). The password may be reset in the reset password function that
	is visible on the login page after setup.

// SETTING UP THE WEBPAGE FOR FIRST TIME USE //
To do this, you require "index.php", "DBPrototype.php", "DBPrototypeLibrary.php", and
access to an FTP server.

1.	ALL THESE FILES MUST BE IN THE SAME FOLDER. THEY SHOULD BE IN THE FOLDER "MTM".
	Place the ENTIRE FOLDER on the FTP server. They should be on the FIRST LEVEL
	of the server and not housed within any other folders for proper redirection,
	or else you will have to edit that within the php files manually.

	NOTE: This is for proper redirection purposes. The current path for redirection is
	set to "MTM/index.php" etc. Please have a professional present to alter any
	link redirects.


2.	Navigate to "yoursite.com/MTM/index.php" in your browser, where "yoursite.com" is the
	domain of your website. "index.php" is the login page of the database. You cannot
	access the other links until you have logged in. It will automatically redirect you
	to "index.php" if you navigate to "DBPrototype.php".

3.	Ensure that all functions are properly running. You should be able to log in with
	the admin account credentials provided above. The admin is capable of adding and
	editting point values and events. Regular users should not be able to see this.