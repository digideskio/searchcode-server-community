To run searchcode server you will need to have any Windows, Linux or OSX machine with Java 8 installed.
Testing and packaging was done using the below version.

java version "1.8.0_65"
Java(TM) SE Runtime Environment (build 1.8.0_65-b17)
Java HotSpot(TM) 64-Bit Server VM (build 25.65-b01, mixed mode)

Uncompress the file you have downloaded to a directory where you want to run searchcode server.
This directory should have more disk space than the size of the repositories you want to index.

Once unpacked assuming that java is in your path (check with the command java -version) you should be able to run
searchcode with the following command

java -jar searchcode-1.0.0.jar

After a few moments searchcode server should be ready to run. By default it will be running on port 8080.
To connect to it enter the following in the browser,

http://SERVER_IP:8080

Be sure to replace SERVER_IP with the ip address if your server or localhost if running locally.
If you see a page with a search bar then everything is fine.

To administer your searchcode server instance you need to click on the Admin link in the top right.
Enter the default password Adm1n234 (change this via the properties file)
to add git repositories. If you need help check the documentation page (link at the bottom
of every page).