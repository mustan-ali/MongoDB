Collection and Document
------------------------
- Collection: A group of documents.
- Document: A set of key-value pairs.

Basic Commands
--------------
- `show dbs` `show databases`: Show all databases
- `use <db>`: Switch to a database
- `show collections`: Show all collections in the current database
- `db.<collection>.find()`: Show all documents in a collection
- `db.<collection>.insert({<key>: <value>})`: Insert a document into a collection
- `db.<collection>.update({<key>: <value>}, {$set: {<key>: <value>}})`: Update a document in a collection
- `db.<collection>.deleteMany({})`: Delete all documents in a collection