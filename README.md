# Programming-Platform

A Programming platform is a platform where a user can see some programming problems and solve them by writing code, and submit that code in that system for judgement. In this project, only authenticated user can enter to the system. Only administrator can set, remove or modify contest and problems. Normal user(problem solver) can participate in contest and solve those problems. The programming language of the submitted code must be in c, c++. Then the system will compile and execute the submitted code and give a verdict to the user. Here the verdict will be one of these (compilation error, right answer, wrong answer, time limit exceed). An user can also modify his profile information.


# Installation

The project can be downloaded from https://github.com/hasantarek2002/Programming-Platform. This project should be installed on a Linux based web server. XAMPP (version 7.2.1) web server for Linux needs to be installed. Then the project should be placed in the htdocs folder inside the xampp folder. 

	/opt/lampp/htdocs/programmingPlaform/imageUpload
	/opt/lampp/htdocs/programmingPlaform/setContest/uploads
	/opt/lampp/htdocs/programmingPlaform/submitAndRunCode/CCode and
	/opt/lampp/htdocs/programmingPlaform/submitAndRunCode/CPPCode

The given directory path access should be changed to all user accesses by writing the following command: 
#chmod 777 directoryPath

C and C++ must be installed in the server computer.

Then we need to create the database by running the following two files

https://github.com/hasantarek2002/Programming-Platform/blob/master/database/createDB.php
https://github.com/hasantarek2002/Programming-Platform/blob/master/database/createAllTables.php

This will create the database for the project.

The URL (Uniform Resource Locator) for accessing this project will be: “ipAddress/programmingPlatform”.

The system will have two types of user. They are: Administrative User and Normal User. They will be provided with two different interfaces with different functionalities. For Example, the administrative user will be able to set, modify and remove contest. But the normal user won’t have the facility of this. They will only be permitted to participate in contests and solve problems.


For Administrative user to login to the system, the default username is” admin” and the default password is”1234”.  By using this username and password the administrative user will be logged in to the system.

