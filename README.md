How to run BDA Lab Software


Pre-requisite software’s:
●	Node (version 16 or above)
●	NPM (version 8 or above)
●	MySQL


Steps to set up environment:

●	Download node from the official node website on windows. In ubuntu run "sudo apt install nodejs”.
●	Check the version of node if installed using “node -v”.
●	Download npm from the official website for npm on windows. In ubuntu run "sudo apt-get install npm".
●	Download the sql files from the bda_lab.zip.
●	Run the sql queries in mysql to create a database.
●	(Note: The database name should be bda_lab and username and password for connecting with mysql should be changed in the code accordingly.)


Steps to run:

●	Unzip BDA_Lab.zip to get all content in a folder.
●	Change directory into the src directory.
●	Open terminal in the src directory.
●	Run command "npm install". If the command throws an error, run "npm install ejs body-parser express mysql2".
●	To start the server write "node server.js".
●	Now you can access the project in your browser by entering the URL "localhost:3000".

Important notes:

●	Ubuntu might install older versions of node and npm. So ensure that you are working with the latest node and npm installations.
●	Some browsers may not give access to run javascript. Allow running javascript in your browser settings.
●	If by some error the program crashes, close the browser window and re-run "node server.js" in the src directory.




Some demo logins:

User_Type	Username	Password
Admin	chandan@gmail.com	chandan
Faculty	bagesh@gmail.com	bagesh
PHD	rajesh@gmail.com	rajesh
MTech	panda@gmail.com	panda
BTech	vishal@gmail.com	vishal

