			Read Me
---------------------------------------------------------------------------------
Application :Stop Corruption

Employeee name:karthik kini
Employee iD:m1016831


Stop Corruption Application:
	This application is an attempt to expose country and their states and departments where corruption is taking place. 
	It allows you to fill out an instance of corruption you have experienced yourself or have knowledge of and share information with the rest of the world.


The application has following features:
	1.Submit a corruption story
	2.Read corruption stories of other people
	3.View yearly corruption report



Softwares Required::
	1.Java Runtime Environment (JRE) version 1.5+
	2.Mysql database version :5.0+
	3.Apache-TomCat version :5.0+

Deliverables:
	1.SQLscripts.txt:contains all DDL amd DML scripts required for the application.
	2.Class design diagram:corruptionClassDiagram.jpeg---->contains Class diagrams from all entity classes used in the application
	3.Entity Relationship diagram:corruptionERDiagram.jpeg--->contains  ER diagram of all the tables used in the application
	4.Test cases:corruption.xlms---->Test case for the use case #1 Submit a corruption story
	5.war file-->StopCorruptionapp.war web application archieve

Deployment procedure:
	1.Run the sql scripts provided in the SQLscripts.txt
	2.Copy the "StopCorruptionapp.war" file into Apache Tomcat server webapps folder [MANUAL DEPLOYMENT]
	3.Start the Apache Tomcat server
	4.Open the Web-browser and type the following in the addrress bar.
		http://server_ipaddress:port/app
		where server_ipaddress refers to the ip address of the server where application is deployed and port  refers to port number used by the server
	5.Follow the instructions provided in the home page.
------------------------------------------------------------------------------------------------------------