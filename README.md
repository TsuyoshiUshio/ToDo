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

Then 

```
npm start
``` 

Hit the `http://localhost:3000` on your browser. Dont' forget to create CosmosDB(SQL DocumentDB) before you start this ToDo apps. 

[Build a Node.js web application using Azure Cosmos DB](https://docs.microsoft.com/en-us/azure/cosmos-db/documentdb-nodejs-application)

You might want to use TypeScript for this purpose, then you can use this.

[Azure Cosmos DB (DocumentDB API) TypeScript interface](https://www.npmjs.com/package/documentdb-typescript)
