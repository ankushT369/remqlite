# remqlite
remqlite is sqlite3 fork with -remote and -connect feature to access data via network 

run: 
```
server: ./remqlite your.db -remote 0.0.0.0:8080
client: ./remqlite -connect 0.0.0.0:8080
```
