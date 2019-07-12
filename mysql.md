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
