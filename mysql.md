# MySql Commands

## Connect to a remote database

**With Password**
```
mysql -u {username} -p {password} \
    -h {remote server ip} -P {port} \
    -D {DB name}
```

**Without Password**
```
mysql -u {username} \
    -h {remote server ip or name} -P {port} \
    -D {DB name} -p
```

## Take dump of remote database
```
mysqldump -P {port} -h {remote server ip} \
    -u {username} -p database_name table_name > dump_file_name.sql
```

## Get list of databases
```
show DATABASES;
```

## Change current database
```
use <DATABASE_NAME>;
```

## List all tables in a database
```
use <DATABASE_NAME>;
show TABLES;
```

## List all rows in a table
```
SELECT * from <TABLE_NAME>;
```

## List only select columns of all rows in a table
```
SELECT <COLUMN_NAME_1>,<COLUMN_NAME_2> from <TABLE_NAME>;
```
