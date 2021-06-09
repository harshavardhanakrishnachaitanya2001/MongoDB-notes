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

### Insert document in collection
```javascript
db.<collectionName>.insert({'key':value})
```
