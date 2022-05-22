# MySql Commands

## Connect to a remote database

**With Password**
```mysql
mysql -u {username} -p {password} \
    -h {remote server ip} -P {port} \
    -D {DB name}
```

**Without Password**
```mysql
mysql -u {username} \
    -h {remote server ip or name} -P {port} \
    -D {DB name} -p
```

## Take dump of remote database
```mysql
mysqldump -P {port} -h {remote server ip} \
    -u {username} -p database_name table_name > dump_file_name.sql
```

## Connect to local MySQL instance
```mysql
mysql -uroot
```

## Get list of databases
```mysql
show DATABASES;
```

## Change current database
```mysql
use <DATABASE_NAME>;
```

## List all tables in a database
```mysql
use <DATABASE_NAME>;
show TABLES;
```

## List all rows in a table
```mysql
SELECT * from <TABLE_NAME>;
```

## List only select columns of all rows in a table
```mysql
SELECT <COLUMN_NAME_1>,<COLUMN_NAME_2> from <TABLE_NAME>;
```

## Insert values in a table
```mysql
INSERT INTO <TABLE_NAME> (<COLUMN_NAME_1>, <COLUMN_NAME_2>, ...)
VALUES (<VALUE_1>, <VALUE_2>);
```
