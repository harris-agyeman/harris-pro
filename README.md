# harris-pro

this is for testing my cloud build and cloud run


The server . js is a java script file that creates a connectin using an http server which also listens on port number 8080
The cloudbuild.yaml creates steps to carry out the cloud build which builds the image docker and also pushes your image to google container registry,SHORT_SHA 

The Dockerfile (basically contains your image)  pulls the image from node:13-slim

