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

Options  for deployment
# 1. Deploy in your local gitlab, gitlab-runner terraform container, spin up ec2 instance, and do the installation.
# 2. github and github actions for deployment, this option deploys the container to Amazon Container registry and runs the workflow pipeline to deploy the application to Amazon Elastic Container Service
# 3. amazon app service 

Following Option 2 for deployment
Deployed to repository, repository url: 
https://github.com/amarjothi/node-hello/blob/main/README.md







