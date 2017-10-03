# ToDo

Node + DocumentDB Sample of the Microsoft official site

The sample ToDo application of this tutorial.

You need to add `config.js` on the repository top directory. 

`config.js`

```js
var config = {}

config.host = "https://COSMOS_DB_HOST_NAME.documents.azure.com:443/";
config.authKey = "COSMOS_DB_PRIMARY_KEY";
config.databaseId = "ToDoList";
config.collectionId = "Items";

module.exports = config;
```

[Build a Node.js web application using Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/documentdb-nodejs-application)
