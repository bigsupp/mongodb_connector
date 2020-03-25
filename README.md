## MongoDBConnect for Mongoose

Node.js module for MongoDB connection with mongoose

Code snippet from https://stackoverflow.com/a/33603577
in this thread https://stackoverflow.com/questions/16226472/mongoose-autoreconnect-option

Example of mongoose connection options:
```
{
  "useUnifiedTopology": true,
  "useNewUrlParser": true,
  "useFindAndModify": false,
  "useCreateIndex": true,
  "auto_reconnect": true,
  "reconnectTries": 180,
  "reconnectInterval": 100,
  "connectTimeoutMS": 1000,
  "socketTimeoutMS": 60000,
  "user": process.env.MONGO_AUTH_USER,
  "pass": process.env.MONGO_AUTH_PASS,
  "authSource": process.env.MONGO_AUTH_DB
}
```
