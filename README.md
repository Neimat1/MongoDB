# MongoDB

MongoDB is 
  + NoSQL: non-relational db, dynamic schemas 
  + Document based: no tables, JSON, key/values
  + Horizontal scalable: sharding "mean load balance for large queries", replications
  
Installation in linux- ubuntu 
  + https://www.mongodb.com/docs/manual/tutorial/install-mongodb-on-ubuntu/
  
```
# to start the mongo shell
~ sudo systemctl start mongod
~ sudo systemctl status mongod
~ mongosh


# list all dbs you have
~ show dbs


# to create db
~ use dbName


# to insertdocument in a collection 
~ db.collectionName.insertOne({key:"value"})


# to list all data in a collection
~ db.collectionName.find({})



```
