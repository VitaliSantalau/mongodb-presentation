


As we know that MongoDB is a database server and the data is stored in these databases. 
Or in other words, MongoDB environment gives you a server that you can start and then create multiple databases on it using MongoDB. 

database contains collections
multiple collections.

In MongoDB, databases hold one or more collections of documents

MongoDB stores documents in collections

These documents contain the data we want to store in the MongoDB database and a single collection can contain multiple documents

The documents are created using the fields. Fields are key-value pairs in the documents

MongoDB documents are composed of field-and-value pairs and have the following structure:



The data stored in the MongoDB is in the format of BSON documents. Here, BSON stands for Binary representation of JSON documents. Or in other words, in the backend, the MongoDB server converts the JSON data into a binary form that is known as BSON and this BSON is stored and queried more efficiently.
In MongoDB documents, you are allowed to store nested data. This nesting of data allows you to create complex relations between data and store them in the same document which makes the working and fetching of data extremely efficient

The value of a field can be any of the BSON data types, including other documents, arrays, and arrays of documents. 

In MongoDB, each document stored in a collection requires a unique _id field that acts as a primary key. If an inserted document omits the _id field, the MongoDB driver automatically generates an ObjectId for the _id field.