# genie
An open-source PHP command line tool that allow you create database tables easily from the command line. It provides a simple syntax that allow you create your database tables from planning stage


## How to Install
* Clone Repository 
* Put Genie in the root directory of your project (  or any directory of your choice )
* open genie file and replace #!/usr/bin/php with the path to your php execution file ( you can get this on linux commandline using the command : which php )
* Prepare your database in the database.plan file
* invoke genie by typing the command : php genie --setup_db database.plan

## Editing Database.plan File
Database.plan is the file that will be read to create the database and its tables. It has a simple syntax. Different Symbols are used to indicate either a database name, table name, or table field.

* &&DatabaseName : This is used to inidicate a database name. All subsequent tables will be created under this database
* **TableName : This is used to indicate a table name
* ->id,int(11) unsigned,auto increment,pk : This indicated a field and its corresponding properties, the first component after the -> sign is the actual file name, with its properties seprated with comma(s). pk is used to indicate a primary key






Developers are welcomed to fork and submit pull requests

Check me out on [ LinkedIn ](www.linkedin.com/in/imohita)
