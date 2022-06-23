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

Options 
# 1. Deploy in your local gitlab
# 2. github and github actions
# 3. amazon app service 

Option 2
Deployed to repository, repository url: 
https://github.com/amarjothi/node-hello/blob/main/README.md





