# music-store-system
It is given ER diagram which describes the workflow of system for renting CDs with albums from different artists. 
Some of the system data is located in the following files: Albums.xml, Artists.xml, DJ.xml, Groups.xml, Singers.xml, CatalogCD.xml, Rent.xml and Client.xml.
Using the previuos files: 
	1. Generate System.xml file that will allow fast and simple access to the informations for Clients and Artists. 
	 a. .Create XML Schema file for System.xml and create the following restrictions:
		-the attribute occupied in the entity CD and the attribute return state in the relation Rent can have values 0,1 and 2 or functional, slightly damaged and damaged.
		-validate the attribute email in the Client entity 
		-the telephone numbers should be in the following format: 75x-yyyy where x is 0-9 digit and y is 1-9 digit
		-the address may not exist, but if it exists should consists two subelemnts (street and number) 
		or it should be in the following format "StreetName St. XX", where StreetName can be string that only contains lower and upper letters, 
		followed by St. and XX or X (X must be digit).
		-the other restrictions should be noticed from the XML files.
	b.Create XQuery expression which will generate the System.xml file from the other .xml files.
	

#### Subject:
Unstructured databases and XML

#### Author:
Teodora Hristovska
