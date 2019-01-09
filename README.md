# SQlite

## Using for a sample aplication.

* Create a database with .sql file
```
sqlite3 database_name.db < sql_file.sql
```

* Start or access your database 
```
sqlite3 database_name
```

* Create a table
```
create table table_name(name1 INT, name2 VARCHAR(45));
```

* Insert in to the table
```
INSERT INTO table_name values (10,'varchar');
```

* Show tables
```
.table
```

* Desc table
``` 
PRAGMA table_info([table_name]);
``` 

* Export a database to .sql file 
```
sqlite3 mydatabase.db .dump > mydatabase.sql
```

## Install 

On ubuntu:

```
>> sudo su
>> apt-get install sqlitebrowser
>> apt-get install sqlite3
>> apt-get install libsqlite3-dev
``` 
