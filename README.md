

## To run locally
```shell
npm install
```

## Start docker containers via docker compose

```shell
docker compose -f mongo.yaml up
```

## Create a database
In `localhost:8080`, create a database named `user-accounts`. 

## Start express server
```shell
node app/server.js
```

## Update user details
On `localhost:3000` update the user details and you will see an entry with current details is stored on database in `mongo-express`
