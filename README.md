# MongoDB-notes
### To create a database/switch between databases
```javascript
use <databasename>
```

### To show all databases
```javascript
show dbs
```

### Show current database
```javascript
db
```

### Drop database
```javascript
db.dropdatabase()
```

### Show collections
```javascript
show collections
```

### Create a collection
```javascript
db.createCollection('<nameOfCollection>')
```

### Drop collection
```javascript
db.<collectionName>.drop()
```

### Insert single document in collection
```javascript
db.<collectionName>.insert({
'key1':value1,
'key2':value2,...
})
```

### Insert many documents
```javascript
db.<collectionName>.insertMany([
{'key1':value1,'key2':value2,...},
{'key1':value1,...},
{'key1':value1,...},...
])
```

### To display all documents in a collection
```javascript
db.<collectionName>.find().pretty()

pretty() is used to display documents in a readable way
```

### Search for specific key value pair in a database
```javascript
db.<collectionName>.find({'key':value})
```

### Limit the number of documents shown in the terminal
```javascript
db.<collectionName>.find().pretty().limit(<numberOfItemsToShow>)
```

### Count the number of documents in the collection
```javascript
db.<collectionName>.find().count()
```

### Count the number of documents with specific key value in the collection
```javascript
db.<collectionName>.find({'key':value}).count()
```

