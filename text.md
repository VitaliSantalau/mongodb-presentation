Hello everyone!
I am Vitaliy Santalau. And I'm going to talk about mongoDB.

So, what is mongoDB.
This is a databases server and the data is stored in these databases. 
Or in other words, MongoDB is an environment where you can create multiple databases using MongoDB.

Let's talk a little about structure database.
So, database contains one or more collections.
Collection stores one or more documents.
And finally, these documents contain the data that we want to store.

You can ask how?
MongoDB uses BSON as data storage format.
Here, BSON stands for Binary representation of JSON documents. Or in other words, in the backend, the MongoDB server converts the JSON data into a binary form that is known as BSON and this BSON is stored and queried more efficiently.

Let's go back to the document

MongoDB documents are composed of field-and-value pairs and have the following structure:

The value of a field can be any of the BSON data types, including other documents, arrays, and arrays of documents
In MongoDB documents, you are allowed to store nested data. This nesting of data allows you to create complex relations between data and store them in the same document which makes the working and fetching of data extremely efficient

I should mention a unique _id field

Each document stored in a collection requires a unique _id field that acts as a primary key. If an inserted document omits the _id field, the MongoDB driver automatically generates an ObjectId for the _id field.
