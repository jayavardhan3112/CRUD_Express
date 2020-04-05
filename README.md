# CRUD app using Express


## Installation

clone the repository
```bash
npm install
```

## Usage

```bash
node server.js
==============
nodemon server.js
```

* make sure that the mongodb is running in the background
* If not installed 
```bash
https://treehouse.github.io/installation-guides/mac/mongo-mac.html
```
* If already installed
```bash
mongod
```
* If you have Mac and updated to Catalina than the root folder is no longer writable. Try this
```bash
mkdir -p Users/user/data/db
sudo chown -R `id -un` /Users/user/data/db
mongod --dbpath=/Users/user/data/db
```
