# Log_Query_interface_CS211
This is course project of CS 211: Log Query interface

#Setting up system:
1) Download eclipse java EE version. <br>
2) Download Apache tomcat 1.7 (it will work with other version, it is preffered to use this. Other version may give conflict)<br>
3) Download repository using git clone, and import the project into eclipse. Use file->import->exisiting project ...<br>
4) To run the project on mysql you need to set up the Mysql database.<br>
5) Mysql database, in the project I have used username and password "root". If you have any other password, update it in the Database_connector class.<br>

#About Spark:
1) If you want to connect to spark, change the "Run_Spark" into true (a private static final variable in Answer_query_servlet). <br>
2) Default spark server IP: localhost:4567. <br> 
