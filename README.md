# esres-bootcamp-workshops

Our CICD tool of choice for this workshop is Jenkins.

Jenkins is an open source automation server. It helps automate the parts of software development related to building, testing, and deploying, facilitating continuous integration and continuous delivery.

This is a tool used widely across Sky and this workshop attempts to locally imitate the deployment process for an app written in python.

The steps for this workshop are as follows:

1. Setup Jenkins locally with a DinD (Docker in Docker Approach)

2. Build a Docker Container Locally and test the Code Works

3. Create your first pipeline to familiarize yourself with Groovy Syntax and then Create a Build Pipeline to Build Your Docker Image

4. Add a stage to Login and Push Your Image to Dockerhub and then test this by pulling the image locally.


# Prerequisites

For this workshop, it is assumed you will have the following:

- Dockerhub Account
- Docker Installed on your machine
- Basic understanding of docker commands
