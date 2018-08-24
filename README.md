# aws-node-sample

A template / sample to build and deploy node and react application to AWS Elastic Beanstalk.

1. npm install
2. npm run dev
   To build and run locally as development environment via webpack-dev-server
3. npm run build-prod
   To build production version for deployment, output to dist folder
4. create/deploy new node.js application in AWS Elastic Beanstalk
   a. Zip everything in dist folder
   b. Upload zip file to AWS Elastic Beanstalk application
5. npm start
   To run the prod-server.js in production enviornment