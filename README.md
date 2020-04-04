# MERNG
This cute little server is built on MERNG-stack
- MongoDB
- ExpressJS
- React
- Node
- GraphQL

Made by following the YouTube-tutorial
https://www.youtube.com/playlist?list=PLMhAeHCz8S3_CTiWMQhL6YxX7vZ7z84Zo

To make this run no your Mongo-db add a config.js in the root-directory containing:

```javascript
module.exports = {
    MONGODB: <MONGODB_CONNSTRING>,
    SECRET_KEY: <SOME_SECRET_KEY>
}
```
- npm install
- npm start