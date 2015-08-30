# rampup-node-api
Node app to practice CRUD that returns JSON

brew install mongodb

mongod --dbpath <path to data directory>

mongoimport --db test --collection <collection name> --drop --file primer-dataset.json

To import data into a mongod instance running on a different host or port, specify the hostname or port by including the --host and the --port options in your mongoimport command.
