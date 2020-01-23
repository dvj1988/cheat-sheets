# Shell Commands

## Create database
  
  ```use <DB name>```

if the db doesnot exist, mongo creates a new db and switches to it.

## Show databases

  ```show dbs```

List all the databases with atleast one collection in it.

## Insert one Document into Collection
```db.CollectionName.insertOne( { x: 1 } )```

if the collection doesnot exist, mongo creates a new collection and inserts the document into it.
