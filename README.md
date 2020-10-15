# MrSister-Backend-API
## Set up mongo DB##
```
brew tap mongodb/brew
```
Once mongo DB is set up, you can install software package with
```
brew install mongodb-community
```
**run project**

To run data into database, open terminal
```
node loadSupplierDataToDB.js
```
(loadSupplierDataToDB this is file name)

To run the project
First we need to install npm for that
```
npm install
```
(this will install all the package in npm)

Optional: if there is any issue you can do:
```
npm audit-fix
```
To run the backen API
```
npm start
```
***(this will start the backend API on localhost:4000 and load all the data into database and ready to go)***


