# Install

Run `npm install` to install dependencies

Config MongoDB URL

```js
// config/database.js
const config = {
  development: {
    port: process.env.PORT || 9999,
    dbURL: "mongodb://localhost:27017/rest-api-db", // Add your MongoDB Collection
    authCookieName: "x-auth-token",
  },
  production: {},
};
```

Run `node index.js` to start the server
