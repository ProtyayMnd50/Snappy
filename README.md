# Snappy - Chat Application 
Snappy is realtime chat application made on MERN stack.


![login page](./images/snappy_login.png)

![home page](./images/snappy.png)

## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

- Both should be installed.Make sure mongodb is running.
- Clone the app using 'gitc clone' command
- Now rename env files from .env.example to .env
```shell
cd public
mv .env.example .env
cd ..
cd server
mv .env.example .env
cd ..
```

- Now install the dependencies
```shell
cd server
yarn
cd ..
cd public
yarn
```
- Start the development server.

For Frontend.
```shell
cd public
yarn start
```
For Backend.

- Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```

Done! Now open localhost:3000 in your browser.(the current localhost on your browser)
