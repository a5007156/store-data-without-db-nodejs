# Receive HTTP requests and store data without using a database (nodejs version)

## HOW TO USE
    sudo apt install git
    git clone https://github.com/Tecosse/store-data-without-db-nodejs-/
    cd ./store-data-without-database/
    node ./server.js
> You can then send HTTP requests to the server to store and retrieve data. For example, you can use the following curl command to send a POST request with some data:

    curl -X POST -H "Content-Type: application/json" -d '{"key": "myKey", "value": "myValue"}' http://localhost:3000

> This will store the data in the in-memory store. You can then retrieve the data using a GET request:

    curl http://localhost:3000?key=myKey

> This will return the data that you previously stored.
