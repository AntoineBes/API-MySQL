# REST API 
## Rest API Using MySQL and NodeJS
## Installation

NodeJS version 16.16.0.
npm version 8.11.0

Install the dependencies and devDependencies and start the server.

```sh
npm i
npm start
```

## Dependencies 

| Dependencies | version | package |
| ------ | ------ | ------ |
| bcryptjs | ^2.4.3 | https://www.npmjs.com/package/bcryptjs |
| cors | 2.8.5 | https://www.npmjs.com/package/cors |
| express | ^4.18.1 | https://www.npmjs.com/package/express |
| jsonwebtoken | ^8.5.1 | https://www.npmjs.com/package/jsonwebtoken |
| nodemon | ^2.0.19 | https://www.npmjs.com/package/nodemon |
| mysql2 | ^2.3.3 | https://www.npmjs.com/package/mysql2 |
| sequelize | ^6.21.3 | https://www.npmjs.com/package/sequelize |

## Accessibility

Find the server port or set new port on `server.js` file.
```sh
const PORT = process.env.PORT || 3880;
app.listen(PORT, () => {
    console.log(`Server is running on port ${PORT}.`);
});
```
```sh
http://localhost:3880
```

## License

MIT

