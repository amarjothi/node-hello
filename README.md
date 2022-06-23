# Node Hello World

Simple node.js app that servers "hello world"

Great for testing simple deployments to the cloud

## Run It

`npm start`

# Build the docker file

docker build . -t amar/node-web-app

docker run -p 49200:3000 -d amar/node-web-app

docker ps

curl http://localhost:49200/

# Deploy in your local gitlab



