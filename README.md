# SimpleFi

## Getting started

1. Clone the repo

```
git https://github.com/vortelus/SimpleFi.git
```

2. Create a .env file in the Prisma directory
```
DB_PORT=<yourport>
DB_USERNAME=<yourusername>
DB_PASSWORD=<yourpassword>
DB_HOST=<yourhost>
DB_NAME=<yourdbname>
DATABASE_URL = postgres://${DB_USERNAME}:${DB_PASSWORD}@${DB_HOST}:${DB_PORT}/${DB_NAME}
```

3. Start the backend server
```
cd server/
npm install
nodemon index.js
```

4. start the client server
```
cd client/
npm install
npm start
```
