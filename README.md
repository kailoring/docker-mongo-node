# Docker Node-Mongo Example

The purpose of this example is to create a docker container and run a sample application using Node.js and MongoDB.

Simply run `docker-compose up`  to initiate.

## Files

### Dockerfile
- Contains commands to assemble an image

### docker-compose.yml
- Defines and configures docker applications  

### index.js 
- Contains model, routes, and set view engine

### package.json
- Bring in dependencies and contains start up script


## Directories

### adr

This directory contains the Architectural Design Records.

### views

This directory contains the file containing the application form to add an item and loop through the list of items.

- `index.ejs`

### models

This directory contains the files necessary to create the item schema for adding items to the list.

- `Item.js`

### data

This direction contains files used to store and maintain database data.
