# RapportRoom - Chat Application 
RapportRoom is chat application build with the power of MERN Stack.

## Installation Guide

### Requirements
- [Nodejs](https://nodejs.org/en/download)
- [Mongodb](https://www.mongodb.com/docs/manual/administration/install-community/)

Both should be installed and make sure mongodb is running.
### Installation

```shell
git clone https://github.com/VishhalYadav/chat-app-mern.git
cd chat-app-mern
```


Now install the dependencies
```shell
cd server
yarn
cd ..
cd client
yarn
```
We are almost done, Now just start the development server.

For Frontend.
```shell
cd client
yarn start
```
For Backend.

Open another terminal in folder, Also make sure mongodb is running in background.
```shell
cd server
yarn start
```
Note - You need to set MONGO_URL inside server folder to valid mongoDB string.

Done! Now open localhost:3000 in your browser.
