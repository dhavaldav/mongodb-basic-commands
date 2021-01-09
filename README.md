# mongodb-basic-commands
basic commands for mongodb

1. find all data MongoDB  
db.collection.find()

2. remove mongoDB All data
#db.collection.remove( { } )
 
3. MongoDB Help

To get a list of commands, type db.help() in MongoDB client. This will give you a list of commands as shown in the following screenshot.
db.help
 
4. Show All Databases

Use below command to get list of all databases.
show dbs

db.version
5. Create new database

To create a new database execute the following command.
use DATABASE_NAME 

6. Know your current selected database

To know your current working/selected database execute the following command
db
 
7. Drop database
To drop the database execute following command, this will drop the selected database
db.dropDatabase()

 
8. Create collection

To create the new collection execute the following commands
db.createCollection(name)

 
9. To check collections list

To get the list of collections created execute the following command
Show collections

 
10. Drop collection

To drop the selected collection execute the following command
db.COLLECTION_NAME.drop()

 
11. Insert document in collection
db.COLLECTION_NAME.insert(document)

To insert single document in selected collection execute the following command

 
To insert multiple documents in selected collection execute following command

 
12. Get collection document

To get the list documents in collection execute the following command
db.COLLECTION_NAME.find()

 
13. Update document

To update the document in collection execute the following command
db.COLLECTION_NAME.update(SELECTION_CRITERIA, UPDATED_DATA)

 
14. Save document

To save document in collection execute the following command
db.COLLECTION_NAME.save({_id:ObjectId(),NEW_DATA})

 
15. Delete document

To delete document in selected collection execute the following command
db.COLLECTION_NAME.remove(DELLETION_CRITTERIA)
 
