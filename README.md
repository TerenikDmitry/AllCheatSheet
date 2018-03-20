# AllCheatSheet
Cheat Sheets for programming

## Shell
[apt](https://blog.packagecloud.io/eng/2015/03/30/apt-cheat-sheet/)

## MongoDB
[manual](https://docs.mongodb.com/manual/)

### Work with mongod
```
sudo service mongod start/stop/restart
```

### Start the mongo Shell
```
mongo
```
To specify a different host or port number
```
mongo -u <user> -p <pass> --host <host> --port 28015
```

### Work with dbs
To show list the available databases
```
show dbs
```
To display the database you are using
```
db
```
To switch databases
```
use <database>
```
To show collections in current database
```
show collections
```
