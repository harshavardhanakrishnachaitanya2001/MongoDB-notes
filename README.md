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

### Insert many rows
```javascript
db.<collectionName>.insertMany([
{'key1':value1,'key2':value2,...},
{'key1':value1,...},
{'key1':value1,...},...
])
```

